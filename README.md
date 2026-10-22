# DataBricks IAP Assessment

<div align="center">
  <svg width="100%" viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Databricks IAP Assessment banner">
    <defs>
      <linearGradient id="bg" x1="0%" x2="100%" y1="0%" y2="100%">
        <stop offset="0%" stop-color="#0f172a"/>
        <stop offset="45%" stop-color="#1d4ed8"/>
        <stop offset="100%" stop-color="#0ea5e9"/>
      </linearGradient>
      <filter id="blur"><feGaussianBlur stdDeviation="20"/></filter>
    </defs>

    <rect x="0" y="0" width="1200" height="260" rx="22" fill="url(#bg)"/>

    <circle cx="170" cy="80" r="90" fill="rgba(255,255,255,0.12)">
      <animate attributeName="cx" values="170;250;170" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="80;40;80" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1050" cy="190" r="110" fill="rgba(255,255,255,0.12)">
      <animate attributeName="cx" values="1050;980;1050" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="190;150;190" dur="8s" repeatCount="indefinite"/>
    </circle>

    <text x="600" y="110" text-anchor="middle" fill="#E0F2FE" font-size="30" font-family="Arial, sans-serif" font-weight="700" letter-spacing="2">
      DATBRICKS • UNITY CATALOG • LAKEHOUSE
    </text>

    <text x="600" y="170" text-anchor="middle" fill="#FFFFFF" font-size="46" font-family="Arial, sans-serif" font-weight="700">
      Sales &amp; Supply Chain Analytics
    </text>

    <text x="600" y="208" text-anchor="middle" fill="#DBEAFE" font-size="22" font-family="Arial, sans-serif">
      End-to-end Data Engineering + Data Analytics using TPC-H
    </text>
  </svg>
</div>

This project is a Databricks-based IAP evaluation built around the TPC-H dataset to model a modern sales and supply-chain lakehouse.

## Overview

The solution follows a Medallion Architecture:

- Bronze: raw ingestion of source TPC-H tables
- Silver: validation, cleansing, and quality checks
- Gold: business-ready aggregated datasets and KPI metrics

## What this project covers

- Unity Catalog target setup in DEV
- Bronze ingestion for core TPC-H tables
- Data quality, validation, and quarantine handling
- Reproducible end-to-end pipeline execution
- Gold analytical tables for revenue and operational insight
- Business analysis using Databricks SQL and PySpark

## Business focus

This project helps answer questions such as:

- How much net sales revenue is generated?
- Which customers, products, countries, and regions drive revenue?
- How are orders and sales trending over time?
- Which suppliers and products need deeper investigation?

## Tech stack

- Databricks
- Unity Catalog
- Delta Lake
- PySpark / SQL

## Project note

TPC-H is a synthetic benchmark dataset used for learning and evaluation. The findings are meant for educational business analysis, not real-world operational claims.

## Reference

This repository follows the Databricks IAP assessment reference for a sales and supply chain lakehouse implementation using TPC-H data.

---

Minimal, scalable, and designed as an end-to-end analytics solution.
