# Apache Solr (apache-solr)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
