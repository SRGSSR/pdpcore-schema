# PDPCore MetaData Schema Specification

This repository contains the schema of [The Publication Data Platform](http://api.pdp.production.srgssr.ch/).

The PDP offers four schemas types.

- [REST OpenAPI](https://github.com/SRGSSR/pdpcore-schema/blob/main/rest/pdp-api.yaml)
- [Avro Ingest](https://github.com/SRGSSR/pdpcore-schema/blob/main/avro/ingest/PDP.avdl) (Deprecated)
- Avro Egest comming soon
- [GraphQL](https://github.com/SRGSSR/pdpcore-schema/blob/main/graphql/pdp.ebucore.v1.deprecated.graphql) (EBUCore deprecated)

It is meant to be used for discussing the schemas and suggesting changes.
Please open a new issue or pull request to start a discussion, ask questions or suggest changes.

## REST Ingest

The primary write API is REST defined in [REST OpenAPI](https://github.com/SRGSSR/pdpcore-schema/blob/main/rest/pdp-api.yaml). It is work in progress. Please refer to Avro implementation for a full PDPCore write schema.

## Avro

The Kafka Avro write API is being depecated. Please use REST if possible because it validates your input data synchronously. The Avro schemas in this repository must not be used by applications that use the PDP. Applications must use the Avro schemas published in the
[Avro schema registry](https://akhq.pdp.production.admin.srgssr.ch/ui/strimzi/schema)

## GraphQL

The [GraphQL schema](https://api.pdp.production.srgssr.ch/graphql/schema.graphql) is backwards compatible.
