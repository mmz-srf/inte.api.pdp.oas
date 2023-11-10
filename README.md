# About

This public repository contains the OpenAPI-Specification (OAS) for the data that the Integrationplatform (INTE)
publishes via the Content API to
the [Publication Data Platform](https://api.pdp.production.srgssr.ch/) (PDP).

Each Provenance has its own OAS in a seperate yml-file which serves as a contract for INTE and PDP and can be used to
generate model-classes for (de-)serialization. 

# Versioning
The version-number for the changed model in the specific yml-file must be changed manually according to the [semantic versioning standard](https://en.wikipedia.org/wiki/Software_versioning).
Each version-change will be reflected by a Git-Tag (e.g v1.5.2) representing the latest state for all models.
