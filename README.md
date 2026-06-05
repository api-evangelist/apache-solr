# Apache Solr (apache-solr)

Apache Solr is an open-source enterprise search platform built on Apache Lucene. It provides distributed indexing, replication, load-balanced querying, automated failover and recovery, and centralized configuration through SolrCloud. Solr exposes comprehensive REST/HTTP APIs for document indexing, full-text search with faceting and highlighting, schema management, collections management, and cluster operations. It is an Apache Software Foundation project used by major organizations for enterprise-scale search solutions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-solr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-solr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Enterprise Search
- Full-Text Search
- Lucene
- Search
- SolrCloud
- Open Source
- Java

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Solr Search API

The Solr Search API provides HTTP endpoints for full-text document search, including query parsers (Standard, DisMax, Extended DisMax), JSON Query DSL, faceting and JSON Facet API, spell checking, suggestions, MoreLikeThis, spatial search, dense vector search, result grouping, highlighting, and result clustering. Queries are submitted to the /select handler and support complex relevancy scoring with Learning to Rank.

- **Human URL:** [https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html](https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html)

#### Tags

- Search
- Faceting
- Full-Text Search
- REST
- Indexing

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html)
- [Documentation](https://solr.apache.org/guide/solr/latest/query-guide/json-request-api.html)
- [Postman Collection](collections/apache-solr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-solr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Solr Indexing API

The Solr Indexing API provides HTTP endpoints for adding, updating, and deleting documents from the search index. It supports JSON, XML, CSV, and binary Solr formats via the /update handler, atomic updates, optimistic concurrency, document routing in SolrCloud, and the DataImportHandler for bulk loading from databases and file systems.

- **Human URL:** [https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html](https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html)

#### Tags

- Indexing
- Documents
- REST
- Updates

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html)
- [Postman Collection](collections/apache-solr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-solr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Solr Schema API

The Solr Schema API provides REST endpoints for managing the schema of a Solr collection, including field types, fields, dynamic fields, and copy fields. The Managed Schema approach allows runtime schema modifications without server restart via the /schema endpoint.

- **Human URL:** [https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html](https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html)

#### Tags

- Schema
- REST
- Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html)
- [Postman Collection](collections/apache-solr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-solr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Solr Collections API

The Solr Collections API provides REST endpoints for managing SolrCloud collections, shards, replicas, and aliases. It supports collection creation, deletion, modification, shard splitting, replica management, collection backup/restore, alias management, and cross-datacenter replication (CDCR) configuration.

- **Human URL:** [https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html](https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html)

#### Tags

- Collections
- SolrCloud
- Cluster
- Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html)
- [Postman Collection](collections/apache-solr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-solr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Solr Config API

The Solr Config API and Request Parameters API provide REST endpoints for managing Solr's solrconfig.xml settings at runtime without server restart, including request handler configuration, search component configuration, query settings, and configset management. The v2 API provides a modern JSON-based interface for all configuration operations.

- **Human URL:** [https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html](https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html)

#### Tags

- Configuration
- REST
- Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html)
- [Postman Collection](collections/apache-solr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-solr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/solr)
- [Documentation](https://solr.apache.org/guide/solr/latest/)
- [Portal](https://solr.apache.org/)
- [Getting Started](https://solr.apache.org/guide/solr/latest/getting-started/introduction.html)
- [Release Notes](https://github.com/apache/solr/releases)
- [Support](https://solr.apache.org/community.html)
- [Terms of Service](https://www.apache.org/licenses/)
- [SDK](https://solr.apache.org/guide/solr/latest/deployment-guide/solrj.html)
- [SDK](https://github.com/apache/solr-operator)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
