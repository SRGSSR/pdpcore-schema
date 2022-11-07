# PDPCore MetaData Schema Specification

This repository contains the PDP schemas.
It is meant to be used for discussing the schemas and suggesting changes.
Please open a new issue or pull request to start a discussion, ask questions or suggest changes.

The schemas in this repository must not be used by applications that use the PDP. 
Applications must use the Avro schemas published in the
[Avro schema registry](https://akhq.pdp.production.admin.srgssr.ch/ui/strimzi/schema)
and the [GraphQL schema](https://api.pdp.production.srgssr.ch/graphql/schema.graphql) provided by the PDP API.

The Publication Data Platform has three schemas types.

- Avro Ingest
- Avro Egest (not yet released)
- GraphQL

## Contributing

1. Fork this repo and create PR with your changes.
