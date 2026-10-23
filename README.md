# Sigma Intelligence Platform — GenAI for Data Engineering

**Proof of Concept (POC) | Sigmoid Bangalore | 2026**

---

## Overview

This repository contains a proof of concept for an AI-native Data Engineering platform. It explores how generative AI and agentic workflows can support key data engineering activities such as SQL review, pipeline generation, data quality validation, governance, lineage, and self-healing.

The components in this repository are experimental and intended to demonstrate possible platform capabilities. They are not presented as a production-ready system.

## POC Objectives

The POC investigates how GenAI can help with:

- Reviewing and improving SQL queries
- Generating data pipelines from natural-language specifications
- Creating dbt models and data engineering scaffolding
- Validating data quality and identifying anomalies
- Detecting sensitive and personally identifiable information (PII)
- Building metadata, lineage, and catalogue information
- Using agents to diagnose and remediate pipeline issues
- Providing natural-language interfaces for data engineering workflows

## Quick Start

```bash
# Clone the repository
git clone https://github.com/Kuwar-Vishnudatt/sigma-genai-de.git
cd sigma-genai-de

# Install base dependencies
pip install -r setup/requirements.txt
```

Individual POC components may have additional dependencies and setup instructions in their respective directories.

## POC Areas

| Area | Focus |
|-----|-------|
| SQL Brain | AI-assisted SQL review, NL2SQL, and dbt scaffolding |
| Pipeline Brain | PySpark and Airflow pipeline generation from English specifications |
| DevOps Brain | Automated tests, GitHub Actions CI/CD, and documentation generation |
| Quality Brain | Data quality validation, log analysis, and RAG-based assistance |
| Agent Core | ReAct and LangGraph-based agent workflows |
| Governance Agent | Data ingestion, PII detection, lineage, and catalogue generation |
| Self-Healing and Natural Language | Automated remediation and English-to-SQL interaction |
| Integration | Demonstration of how the individual capabilities can work together |

## Repository Structure

```text
├── setup/              ← Base environment setup
├── day6/               ← SQL review and data engineering foundations
├── day7/               ← Pipeline generation
├── day8/               ← Testing, CI/CD, and documentation
├── day9/               ← Data quality and RAG workflows
├── day10/              ← Agentic AI workflows
├── day11/              ← Intelligent ingestion and governance
├── day12/              ← Self-healing and natural-language workflows
├── day13/              ← Platform integration
└── capstone/           ← Integrated POC demonstrations
```

Each component may include implementation code, sample data, configuration, and a README with specific execution instructions.

## Technology Stack

| Purpose | Tool |
|---------|------|
| LLM | AWS Bedrock Nova Lite/Pro |
| Agent framework | LangGraph |
| Data modelling | dbt Core |
| Data quality | Great Expectations |
| Testing | pytest |
| CI/CD | GitHub Actions |
| Warehouse | Snowflake |
| Local/fallback LLM | Ollama (qwen2.5:7b) |
| Editor | VS Code |

## Scope and Limitations

- This repository is a technical POC intended for exploration and demonstration.
- The examples may require adaptation before use in a production environment.
- Model outputs should be reviewed and validated before being applied to data or infrastructure.
- API keys and credentials must be provided through environment variables or local configuration and must not be committed to the repository.
- Performance, security, cost, and operational characteristics have not been fully evaluated.

## Status

The POC is under active development. Features and implementations may change as different GenAI approaches are evaluated.

---

*GenAI for Data Engineering POC | Sigmoid Bangalore | 2026*
