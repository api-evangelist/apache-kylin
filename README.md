# Apache Kylin (apache-kylin)

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

Apache Kylin is an open-source distributed analytics engine providing a SQL interface and multi-dimensional analysis (OLAP) on large-scale datasets with sub-second query latency on trillion-record datasets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-kylin/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Big Data, Cube, OLAP, Open Source, SQL

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Kylin REST API
The Kylin REST API provides endpoints for SQL query execution, model management, project management, and job management.

**Human URL:** [https://kylin.apache.org/docs/restapi/](https://kylin.apache.org/docs/restapi/)

#### Tags:

 - JDBC, OLAP, REST, SQL

#### Properties

- [Documentation](https://kylin.apache.org/docs/restapi/)
- [OpenAPI](openapi/apache-kylin-rest-api.yaml)

### Apache Kylin JDBC Driver
The Kylin JDBC driver provides SQL-over-Kylin access for BI tools and SQL clients.

**Human URL:** [https://kylin.apache.org/docs/tutorial/jdbc.html](https://kylin.apache.org/docs/tutorial/jdbc.html)

#### Tags:

 - JDBC, SQL

#### Properties

- [Documentation](https://kylin.apache.org/docs/tutorial/jdbc.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/kylin)
- [Documentation](https://kylin.apache.org/docs/)
- [GettingStarted](https://kylin.apache.org/docs/tutorial/kylin_sample.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://kylin.apache.org/download/)
- [SpectralRules](rules/apache-kylin-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-kylin-vocabulary.yaml)
- [NaftikoCapability](capabilities/olap-analytics.yaml)

## Features

| Name | Description |
|------|-------------|
| Sub-Second OLAP Queries | Pre-computed cubes enable sub-second query response on trillion-record datasets. |
| SQL Interface | ANSI SQL interface for business analysts using existing SQL skills. |
| Cube Pre-computation | Build cubes with aggregates pre-calculated for instant query response. |
| Hadoop and Cloud Integration | Works on top of Hadoop, Spark, and cloud object storage. |
| JDBC/ODBC Drivers | Standard JDBC and ODBC drivers for BI tool integration. |
| Segment Management | Incremental cube building with date-range segment management. |
| Multi-Tenancy | Project-based multi-tenancy for isolating datasets and access. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Warehouse Query Acceleration | Accelerate slow Hive or Spark queries with Kylin cube pre-computation. |
| BI Tool Integration | Connect Tableau, PowerBI, and Superset to Kylin via JDBC for analytics. |
| Real-Time OLAP | Stream data into Kylin incrementally for near-real-time OLAP analytics. |
| Large-Scale Reporting | Generate business reports over trillion-record datasets in seconds. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Reads from HDFS and executes MapReduce cube builds on Hadoop. |
| Apache Spark | Spark-based cube building for faster and more efficient data processing. |
| Apache Hive | Hive metastore integration for table schema and metadata. |
| Apache HBase | HBase storage for pre-computed cube data. |
| Tableau | Native Tableau connector via Kylin JDBC driver. |
| Apache Superset | Apache Superset integration via JDBC for self-service analytics. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Kylin REST API](openapi/apache-kylin-rest-api.yaml)

### JSON Schema

8 schema files extracted from the REST API OpenAPI specification.

### JSON Structure

8 JSON Structure files converted from JSON Schema files.

### Examples

8 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Kylin REST API](capabilities/shared/kylin-rest-api.yaml) — 3 operations for SQL queries, project listing, and job management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Kylin OLAP Analytics](capabilities/olap-analytics.yaml) | Apache Kylin REST API | 5 | Data Analyst, BI Engineer |

## Vocabulary

- [Apache Kylin Vocabulary](vocabulary/apache-kylin-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 7 actions, 1 workflow, and 2 personas

## Rules

- [Apache Kylin Spectral Rules](rules/apache-kylin-spectral-rules.yml) — 12 rules across 7 categories enforcing Apache Kylin REST API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
