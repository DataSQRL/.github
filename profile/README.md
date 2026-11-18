## Agentic data engineering for operational data

DataSQRL is an open-source harness for agentic data engineering on operational data. It extends coding agents with a SQL compiler, validator, and event-time simulator. Agents build real-time pipelines, data APIs, and data products on Kafka, Flink, Postgres, Iceberg, Spark, Snowflake, and DuckDB, and the compiler verifies them across every system before deployment. Apache 2.0 licensed, it runs on your infrastructure.

### When to use DataSQRL

- You need a data API (GraphQL, REST, or MCP) over operational data.
- You build an operational data product with data quality and observability.
- Kafka is in the pipeline, as source, sink, or both.
- Results are needed in seconds or minutes, not after the next batch run.
- An application, a customer, or an AI agent consumes the output, not only a dashboard.
- You are capturing changes from operational systems into data streams or data lakes.

It is not the fit when the work is dbt models on a schedule inside Snowflake, BigQuery, or Databricks. [See how DataSQRL compares](https://docs.datasqrl.com/docs/intro/comparison).

### Get started

- **[sqrl](https://github.com/DataSQRL/sqrl)**: the DataSQRL harness: compiler, validator, simulator, and the core agent
- **[Documentation](https://docs.datasqrl.com)**: [Getting Started](https://docs.datasqrl.com/docs/intro/getting-started), concepts, and reference
- **[datasqrl-plugin](https://github.com/DataSQRL/datasqrl-plugin)**: run the advanced agent from Claude Code, Codex, Cursor, or GitHub Copilot
- **[datasqrl-examples](https://github.com/DataSQRL/datasqrl-examples)**: self-contained pipelines, data APIs, and data products

Questions and feedback: [GitHub Discussions](https://github.com/DataSQRL/sqrl/discussions).
