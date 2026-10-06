# Awesome-Serverless-Data-Integration-ETL

## Top Serverless Data Integration & ETL Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on ELT Pipelines, Data Transformation & Self-Hosted Integration Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial data integration platforms** and **open-source projects** that extract, load, and transform data across databases, APIs, SaaS applications, and data warehouses. These tools range from serverless ETL services to code-first transformation frameworks.



**Examples** include AWS Glue, Fivetran, Airbyte, Hevo Data, Matillion, Azure Data Factory, Google Cloud Dataflow, Talend Data Fabric, dbt Cloud, and Informatica Cloud (the category leaders).



**Open-source emphasis**: Data integration is one of the strongest open-source domains. **Airbyte** leads with 300+ connectors, **Meltano** brings Singer-based ELT, **dbt** dominates SQL transformation, and **Apache Airflow** orchestrates pipelines. **Apache SeaTunnel**, **Apache NiFi**, and **Benthos** handle data movement, while **Singer** provides the open ELT specification. **dlt** brings Python-native data loading. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Glue](https://aws.amazon.com/glue/)**  

  **AWS's serverless data integration service** — discover, prepare, and combine data for analytics . **Glue Studio for visual ETL** and **Glue DataBrew for no-code data prep** . **Best for AWS-native ETL** .



- **[Fivetran](https://www.fivetran.com/)**  

  **The leading managed ELT platform** — 500+ connectors with automatic schema evolution . **Zero-maintenance pipelines** . **Best for enterprise ELT** .



- **[Airbyte](https://airbyte.com/)**  

  **Managed version of the leading open-source ELT platform** — 300+ connectors . **Best for open-source ELT with managed convenience** .



- **[Hevo Data](https://hevodata.com/)**  

  **No-code data pipeline platform** — 150+ connectors with automatic schema mapping . **Best for no-code ETL** .



- **[Matillion](https://www.matillion.com/)**  

  **Cloud-native data transformation** — visual ETL for Snowflake, BigQuery, Redshift, and Databricks . **Best for cloud data warehouse transformation** .



- **[Azure Data Factory](https://azure.microsoft.com/en-us/products/data-factory/)**  

  **Microsoft's cloud ETL service** — 90+ connectors with visual pipeline design . **Best for Azure-native ETL** .



- **[Google Cloud Dataflow](https://cloud.google.com/dataflow)**  

  **Google's fully managed stream and batch processing** based on Apache Beam . **Best for unified batch/stream pipelines** .



- **[Talend Data Fabric](https://www.talend.com/)**  

  **Enterprise data integration platform** — cloud-native with data quality and governance . **Best for enterprise integration** .



- **[dbt Cloud](https://www.getdbt.com/)**  

  **Managed dbt platform** — SQL-based transformation with scheduling, CI/CD, and documentation . **Best for analytics engineering** .



- **[Informatica Cloud](https://www.informatica.com/)**  

  **Enterprise iPaaS** — data integration, quality, and governance at scale . **Best for large enterprises** .



## Open-Source GitHub Projects



### ELT Platforms



- **[Airbyte](https://github.com/airbytehq/airbyte)**  

  **The leading open-source ELT platform**, MIT licensed with **16,000+ GitHub stars** . **300+ connectors for databases, APIs, and SaaS applications** . **Self-hosted or cloud** — full data control . **The de facto open-source Fivetran alternative** . **Best for open-source ELT at scale** .



- **[Meltano](https://github.com/meltano/meltano)**  

  **Open-source ELT platform built on Singer**, MIT licensed . **500+ taps and targets** — extract, load, and transform . **Best for Singer-based ELT pipelines** .



- **[Singer](https://github.com/singer-io)**  

  **The original open-source ELT specification** — taps (extract) and targets (load) . **The foundation for Meltano and other ELT tools** . **Best for understanding ELT architecture** .



- **[Apache SeaTunnel](https://github.com/apache/seatunnel)**  

  **High-performance data integration platform**, Apache-2.0 licensed . **Batch and stream processing with 100+ connectors** . **Best for large-scale data integration** .



- **[dlt (data load tool)](https://github.com/dlt-hub/dlt)**  

  **Python-native data loading library**, Apache-2.0 licensed . **Load data from APIs and databases with minimal code** . **The simplest way to build custom ELT** . **Best for Python developers** .



### Data Transformation



- **[dbt (data build tool)](https://github.com/dbt-labs/dbt-core)**  

  **The standard for SQL-based data transformation**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Version-controlled SQL with testing, documentation, and lineage** . **The reference for analytics engineering** . **Best for SQL transformation** .



- **[SQLMesh](https://github.com/TobikoData/sqlmesh)**  

  **Next-generation data transformation framework**, Apache-2.0 licensed . **Virtual data environments and column-level lineage** . **Best for advanced transformation workflows** .



- **[Apache Spark](https://github.com/apache/spark)**  

  **Unified analytics engine for large-scale data processing**, Apache-2.0 licensed with **39,000+ GitHub stars** . **Batch and stream processing with SQL, DataFrame, and ML APIs** . **Best for large-scale transformation** .



- **[Apache Flink](https://github.com/apache/flink)**  

  **Stateful stream processing**, Apache-2.0 licensed with **24,000+ GitHub stars** . **Exactly-once semantics and event-time processing** . **Best for real-time transformation** .



### Data Movement & Integration



- **[Apache NiFi](https://github.com/apache/nifi)**  

  **Open-source data flow automation**, Apache-2.0 licensed with **4,000+ GitHub stars** . **Visual programming for data routing, transformation, and ingestion** . **Best for data flow management** .



- **[Benthos (Redpanda Connect)](https://github.com/redpanda-data/connect)**  

  **Stream processing without code**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Declarative YAML configuration for streaming ETL** . **Hundreds of connectors** . **Best for code-free stream pipelines** .



- **[Embulk](https://github.com/embulk/embulk)**  

  **Pluggable bulk data loader**, Apache-2.0 licensed . **Parallel data loading between databases and storage** . **Best for batch data ingestion** .



- **[Apache Camel](https://github.com/apache/camel)**  

  **Integration framework with 300+ connectors**, Apache-2.0 licensed . **Enterprise integration patterns** . **Best for complex integration** .



### Orchestration



- **[Apache Airflow](https://github.com/apache/airflow)**  

  **The standard for workflow orchestration**, Apache-2.0 licensed with **35,000+ GitHub stars** . **Python-based DAGs for scheduling and monitoring pipelines** . **The de facto open-source orchestration tool** . **Best for pipeline orchestration** .



- **[Dagster](https://github.com/dagster-io/dagster)**  

  **Data orchestration with asset graph**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Software-defined assets with observability** . **Best for modern data orchestration** .



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  **Python-native workflow orchestration**, Apache-2.0 licensed with **15,000+ GitHub stars** . **Dynamic workflows with retries and caching** . **Best for Python data pipelines** .



- **[Kestra](https://github.com/kestra-io/kestra)**  

  **Declarative orchestration platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **YAML-based workflows with 500+ plugins** . **Best for declarative orchestration** .



### Additional Strong Open-Source Options



- **Apache Sqoop** — Hadoop data transfer (retired) .

- **Logstash** — Data collection and transformation .

- **Fluentd** — Unified logging layer .

- **Vector** — Observability data pipeline .

- **Apache Beam** — Unified batch and stream processing .

- **Debezium** — CDC platform for database events .

- **Kafka Connect** — Source/sink connectors for Kafka .

- **Pentaho Data Integration** — Visual ETL (Kettle) .

- **Apache Hop** — Modern data orchestration .

- **Talend Open Studio** — Open-source ETL .



**Frameworks for building custom data integration solutions**: Combine **Airbyte** for ELT with 300+ connectors . Use **dbt** for SQL transformation with testing and documentation . Deploy **Apache Airflow** or **Dagster** for orchestration . Choose **Apache SeaTunnel** for large-scale data integration . Integrate **dlt** for Python-native data loading . Use **Apache NiFi** or **Benthos** for visual or declarative pipelines . Note that true serverless data integration with managed infrastructure, automatic scaling, and vendor-supported SLAs (AWS Glue, Fivetran, Matillion) remains primarily commercial territory; open-source stacks provide strong ELT, transformation, and orchestration foundations that require integration for complete data pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data integration platforms handle sensitive business data in motion. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: Airbyte uses MIT, dbt uses Apache-2.0, Airflow uses Apache-2.0, and Meltano uses MIT. All permissive for commercial use. Verify licensing against your use case before committing .

- **Open-source ELT requires operational expertise** — connectors, orchestration, and monitoring require maintenance. Managed platforms shift this responsibility to the vendor.

- **Data quality and schema evolution are critical** — ELT pipelines must handle schema changes, late data, and exactly-once semantics. Test thoroughly before production .

- The open-source ecosystem provides strong ELT, transformation, and orchestration foundations, but **managed infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for data engineers, analytics engineers, and organizations seeking data integration sovereignty.**  

Let's make serverless data integration and ETL more open, transparent, and reliable.
