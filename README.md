# 🚲 BrusselsBike Modern Data Platform

Production-grade unified data platform on Azure Databricks serving batch analytics AND real-time operations for a fictional bike-sharing company.

## 📋 Project Status

Track progress on the [project board](../../projects).

**Phase:** Setup (Week 1)
**Timeline:** Nov 10 – Dec 14, 2026
**Status:** 🟢 In progress

## 🎯 What This Project Demonstrates

- End-to-end Medallion Lakehouse (Bronze/Silver/Gold)
- Real-time streaming with Structured Streaming + watermarking
- Unity Catalog governance with RBAC and PII masking
- Delta Live Tables with quality expectations
- Databricks Workflows orchestration
- System-table-based observability
- Databricks Asset Bundles for CI/CD

## 🏗️ Architecture

*(Coming in Week 5 — see [docs/architecture.md](docs/architecture.md))*

## 🛠️ Tech Stack

- Azure Databricks Premium
- Unity Catalog
- Delta Live Tables (DLT)
- Structured Streaming + Azure Event Hubs
- PySpark + SQL
- Databricks Workflows + Asset Bundles

## 📁 Repository Structure

├── docs/ — Architecture, ADRs, client brief
├── unity-catalog/ — UC setup scripts
├── batch/ — Batch pipelines (Bronze → Silver → Gold)
├── streaming/ — Real-time pipelines + alerts
├── workflows/ — Databricks Workflow configs
├── monitoring/ — System table observability queries
├── dashboard/ — Databricks SQL dashboard exports
└── databricks-bundle.yml — CI/CD config


## 👤 About

Built by **Subhash Kushwaha** — Observability Engineer transitioning to AI & Data Platform Architect.

Microsoft Certified: Fabric Data Engineer Associate (DP-700) | Azure Fundamentals (AZ-900) | Azure Data Fundamentals (DP-900)

[LinkedIn](https://linkedin.com/in/subhash-singh-kushwaha-123281144)