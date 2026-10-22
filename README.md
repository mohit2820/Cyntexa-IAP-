# DataBricks IAP Assessment

<div align="center">
  <div class="hero">
    <span class="badge">Databricks • Unity Catalog • Lakehouse</span>
    <h1>Sales & Supply Chain Analytics</h1>
    <p>End-to-end Data Engineering + Data Analytics project using TPC-H</p>
  </div>
</div>

<style>
  .hero {
    position: relative;
    overflow: hidden;
    padding: 32px 20px;
    border-radius: 18px;
    background: linear-gradient(135deg, #0f172a, #1d4ed8, #0ea5e9);
    box-shadow: 0 20px 45px rgba(14, 165, 233, 0.25);
    margin: 20px 0 28px;
    animation: glow 5s ease-in-out infinite alternate;
  }
  .hero::before {
    content: "";
    position: absolute;
    inset: -40% -10% auto auto;
    width: 220px;
    height: 220px;
    background: rgba(255,255,255,0.14);
    border-radius: 50%;
    filter: blur(12px);
    animation: float 8s ease-in-out infinite;
  }
  .hero::after {
    content: "";
    position: absolute;
    inset: auto auto -30% -10%;
    width: 200px;
    height: 200px;
    background: rgba(255,255,255,0.12);
    border-radius: 50%;
    filter: blur(10px);
    animation: float 10s ease-in-out infinite reverse;
  }
  .badge {
    display: inline-block;
    padding: 8px 14px;
    border-radius: 999px;
    background: rgba(255,255,255,0.12);
    border: 1px solid rgba(255,255,255,0.18);
    color: #e0f2fe;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    margin-bottom: 10px;
  }
  .hero h1 {
    position: relative;
    z-index: 1;
    margin: 0;
    color: white;
    font-size: clamp(28px, 5vw, 52px);
    line-height: 1.1;
  }
  .hero p {
    position: relative;
    z-index: 1;
    margin: 10px 0 0;
    color: #dbeafe;
    font-size: 16px;
  }
  @keyframes float {
    0%, 100% { transform: translateY(0px) scale(1); }
    50% { transform: translateY(-18px) scale(1.08); }
  }
  @keyframes glow {
    0% { box-shadow: 0 20px 45px rgba(14, 165, 233, 0.2); }
    100% { box-shadow: 0 25px 60px rgba(37, 99, 235, 0.35); }
  }
</style>

This project is a Databricks-based IAP evaluation built around the TPC-H sample dataset to model a modern sales and supply-chain lakehouse.

## Overview

The solution follows a Medallion Architecture:

- Bronze: raw ingestion of the source TPC-H tables
- Silver: validation, cleansing, and data quality enforcement
- Gold: curated business datasets and KPI reporting

## What this project covers

- Unity Catalog target setup in a DEV environment
- Bronze ingestion for all core TPC-H tables
- Data quality checks and validation logic
- Re-runnable processing for consistent ingestion
- Gold analytics tables for revenue and operational insights
- Business question analysis using SQL and Databricks

## Business focus

This project helps answer questions such as:

- How much net sales revenue is generated?
- Which customers, products, countries, and regions contribute most?
- How are orders and sales changing over time?
- Which suppliers and products need deeper review?

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

Minimal, scalable, and built as an end-to-end analytics solution.
