# AML Transaction Monitoring Alert Quality Analytics

## Overview
This project demonstrates a transaction monitoring alert quality analysis framework
commonly used in AML and financial crime compliance programs.

The analysis focuses on measuring alert effectiveness, investigator capacity, and
false-positive drivers while balancing operational efficiency against regulatory risk.

---

## Key Analysis Areas

### 1. Alert Volume vs True-Positive Proxy
- Measures alert volume by rule and customer risk tier
- Uses escalation outcomes (case creation, SAR drafting) as a proxy for true positives
- Identifies rules generating high operational noise with limited investigative value

### 2. Investigator SLA & Backlog Trends
- Tracks investigation turnaround time and SLA breaches
- Analyzes backlog aging to identify capacity and resourcing risk
- Highlights periods of operational stress caused by alert spikes

### 3. False-Positive Reduction Lens
- Evaluates rule-level false-positive rates
- Identifies customers generating repeated low-risk alerts
- Supports rule tuning, suppression logic, and segmentation strategies

### 4. Operational Efficiency vs Compliance Risk
- Quantifies trade-offs between alert reduction and risk coverage
- Identifies low-yield rules for optimization
- Maintains regulator-ready documentation for rule governance decisions

---

## Tools & Methods
- SQL (platform-agnostic; compatible with Snowflake, BigQuery, Oracle, Teradata)
- Compliance analytics best practices
- Risk-based alert optimization frameworks

---

## Notes
This project focuses on analytical logic and compliance decision-making rather than
environment-specific execution. The SQL is execution-ready and designed for institutional
AML data environments. Sample outputs are omitted to preserve confidentiality and reflect
real-world compliance workflows.
