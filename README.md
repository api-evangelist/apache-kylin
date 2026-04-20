# Apache Kylin (apache-kylin)
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
