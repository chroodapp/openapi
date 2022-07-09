# Chrood's OpenAPI Specification

This repository contains [OpenAPI specifications](https://www.openapis.org) for Chrood's API.

Files can be found in the `/openapi` directory:

- `spec3.yaml`: OpenAPI 3.0 spec matching the latest version of the public Chrood API.

## Vendor extensions

Extensions (also referred to as specification extensions or vendor extensions) are custom properties that start with `x-`. They can be used to describe extra functionality that is not covered by the standard OpenAPI Specification. Extensions are supported on the root level of the API spec and in the following places:

- `info` section
- `paths` section, individual paths and operations
- operation parameters
- `responses`
- `tags`
- security schemes

At the moment, Chrood's OpenAPI specification does not support vendor extensions. However, we are in the midst of designing vendor extensions that will benefit both the developer and the consumer of the API.
