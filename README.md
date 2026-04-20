# Apache Solr (apache-solr)
Apache Solr is an open-source enterprise search platform built on Apache Lucene. It provides distributed indexing, replication, load-balanced querying, automated failover and recovery, and centralized configuration through SolrCloud. Solr exposes comprehensive REST/HTTP APIs for document indexing, full-text search with faceting and highlighting, schema management, collections management, and cluster operations.

**URL:** [https://solr.apache.org/](https://solr.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Enterprise Search, Full-Text Search, Lucene, Search, SolrCloud, Open Source, Java

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Solr Search API
The Solr Search API provides HTTP endpoints for full-text document search, including query parsers (Standard, DisMax, Extended DisMax), JSON Query DSL, faceting, spell checking, MoreLikeThis, spatial search, dense vector search, result grouping, and highlighting.

**Human URL:** [https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html](https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html)

#### Tags:

 - Search, Faceting, Full-Text Search, REST, Indexing

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/query-guide/query-syntax-and-parsers.html)
- [Documentation](https://solr.apache.org/guide/solr/latest/query-guide/json-request-api.html)

### Apache Solr Indexing API
The Solr Indexing API provides HTTP endpoints for adding, updating, and deleting documents from the search index. It supports JSON, XML, CSV, and binary Solr formats via the /update handler, atomic updates, and document routing in SolrCloud.

**Human URL:** [https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html](https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html)

#### Tags:

 - Indexing, Documents, REST, Updates

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/indexing-guide/indexing-with-update-handlers.html)

### Apache Solr Schema API
The Solr Schema API provides REST endpoints for managing the schema of a Solr collection, including field types, fields, dynamic fields, and copy fields via the /schema endpoint.

**Human URL:** [https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html](https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html)

#### Tags:

 - Schema, REST, Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/indexing-guide/schema-api.html)

### Apache Solr Collections API
The Solr Collections API provides REST endpoints for managing SolrCloud collections, shards, replicas, and aliases. It supports collection creation, deletion, shard splitting, replica management, backup/restore, and alias management.

**Human URL:** [https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html](https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html)

#### Tags:

 - Collections, SolrCloud, Cluster, Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/deployment-guide/cluster-node-management.html)

### Apache Solr Config API
The Solr Config API provides REST endpoints for managing Solr's configuration at runtime without server restart, including request handler and search component configuration. The v2 API provides a modern JSON-based interface.

**Human URL:** [https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html](https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html)

#### Tags:

 - Configuration, REST, Management

#### Properties

- [Documentation](https://solr.apache.org/guide/solr/latest/configuration-guide/config-api.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/solr)
- [Documentation](https://solr.apache.org/guide/solr/latest/)
- [Portal](https://solr.apache.org/)
- [GettingStarted](https://solr.apache.org/guide/solr/latest/getting-started/introduction.html)
- [ReleaseNotes](https://github.com/apache/solr/releases)
- [Support](https://solr.apache.org/community.html)
- [TermsOfService](https://www.apache.org/licenses/)
- [SolrJ Java Client](https://solr.apache.org/guide/solr/latest/deployment-guide/solrj.html)
- [Solr Kubernetes Operator](https://github.com/apache/solr-operator)

## Features

| Name | Description |
|------|-------------|
| Full-Text Search | Comprehensive full-text search with tokenization, stemming, synonyms, and relevance scoring. |
| SolrCloud | Distributed search and indexing with automatic sharding, replication, and ZooKeeper coordination. |
| Faceted Search | Dynamic faceting including field facets, range facets, pivot facets, and JSON Facet API. |
| Streaming Expressions | SQL-like streaming expressions for distributed corpus analytics and aggregations. |
| Dense Vector Search | Approximate nearest neighbor (ANN) search for AI/ML vector embeddings using HNSW algorithm. |
| Learning to Rank | Machine learning-based relevancy tuning with custom feature extraction and model training. |
| Real-Time Get | Near-real-time document retrieval before documents are committed to the index. |
| Spatial Search | Geographic and spatial search with distance filtering and bounding box queries. |
| SQL Interface | SQL query language with JDBC support for analytics tools like Zeppelin and R. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Search | Unified enterprise search across documents, databases, web content, and file systems. |
| E-Commerce Product Search | Product catalog search with faceting, filtering, and recommendation engines. |
| Log Analytics | Log ingestion and search for operational intelligence and security analysis. |
| AI/ML Vector Search | Semantic and similarity search using dense vector embeddings from AI models. |
| Content Management Search | Full-text search backend for CMS platforms and digital asset management systems. |

## Integrations

| Name | Description |
|------|-------------|
| Apache ZooKeeper | Distributed coordination service for SolrCloud cluster management and configuration. |
| Apache Kafka | Stream ingestion via Kafka connector for real-time document indexing. |
| Kubernetes | Solr Kubernetes Operator for cloud-native deployment and management. |
| Grafana | Metrics integration via Prometheus exporter for Solr cluster monitoring. |
| Apache Tika | Document parsing for indexing rich content like PDFs, Word documents, and HTML. |
| Apache NiFi | Data flow integration for automated document ingestion pipelines. |
| OpenNLP | Natural language processing integration for text analysis and named entity recognition. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
