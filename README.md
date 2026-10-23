# dbt_wizard

A simple dbt project created to try out **dbt Wizard**, dbt's AI agent for
analytics engineers. The goal is to see how well Wizard understands a dbt
project and how it handles everyday tasks.

## What this project does
- Models [source data, e.g. raw orders] into staging and mart layers
- Includes basic tests and documentation in `schema.yml`
- Used as a sandbox for Wizard workflows: [e.g. generating models,
  adding tests, renaming columns, explaining lineage]

## Stack
- dbt [Core / Fusion / platform]
- Warehouse: [DuckDB / Snowflake / BigQuery / Databricks]
- AI tooling: dbt Wizard ([CLI / platform])

## What I'm exploring
- How Wizard plans changes and validates them with `dbt parse` and `dbt build`
- How it uses project context (lineage, tests, contracts)
- Where it saves time, and where it needs guidance
