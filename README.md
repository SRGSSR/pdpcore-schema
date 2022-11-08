# PDPCore MetaData Schema Specification

This repository contains the PDP schemas.
It is meant to be used for discussing the schemas and suggesting changes.
Please open a new issue or pull request to start a discussion, ask questions or suggest changes.

The schemas in this repository must not be used by applications that use the PDP. 
Applications must use the Avro schemas published in the
[Avro schema registry](https://akhq.pdp.production.admin.srgssr.ch/ui/strimzi/schema)
and the [GraphQL schema](https://api.pdp.production.srgssr.ch/graphql/schema.graphql) provided by the PDP API.

The Publication Data Platform has three schemas types.

- [Avro Ingest](https://github.com/SRGSSR/pdpcore-schema/blob/main/avro/ingest/PDP.avdl)
- Avro Egest (not yet released)
- [GraphQL](https://github.com/SRGSSR/pdpcore-schema/blob/main/graphql/pdp.ebucore.v1.deprecated.graphql) (EBUCore deprecated)
