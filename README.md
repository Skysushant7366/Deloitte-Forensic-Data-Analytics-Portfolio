# Deloitte Forensic Data Analytics Portfolio

## Professional Profile & Technical Narrative
Forensic Data Analyst specializing in **operational telemetry** and **corporate equity auditing**. Proven track record distilling high-stakes business intelligence from fragmented data environments.

Completed Deloitte Australia Data Analytics simulation, architecting data solutions for **Daikibo Industrials**—transforming raw multi-level JSON schemas and complex Excel datasets into authoritative insights. Expertise bridges technical data engineering with executive-level decision-making through forensic investigation and advanced visualization.

---

## Core Technical Competency Matrix

| Category | Skills | Context |
|----------|--------|---------|
| **Data Engineering** | Data Structures, Programming (Python), Computer Networking | Applied to understand data unification algorithms synthesizing global telemetry into single JSON file |
| **Analysis & Visualization** | Tableau, Excel, Data Modeling, Spreadsheet Skills | Leveraged Tableau for multi-factory downtime modeling; Excel for forensic pay equality classification using nested logical functions |
| **Operational Strategy** | Log Analysis, Planning, Formal Communication | Interpreted 10-minute interval telemetry messages to identify failure patterns and synthesize findings for Forensic Tech team |

---

## Project 1: Daikibo Machine Telemetry Analysis (Tableau)

### Context
Large-scale analysis of operational telemetry across four global manufacturing hubs: **Tokyo (Meiyo)**, **Osaka (Seiko)**, **Berlin**, and **Shenzhen**.

### Technical Execution
- **Schema Ingestion**: Decompressed and imported `daikibo-telemetry-data.json.zip`, preserving multi-level JSON hierarchies
- **Calculated Measure**: Engineered custom **"Unhealthy"** status measure (weight of 10 = 10 minutes potential downtime)
- **Visualization**: Built **"Down Time per Factory"** and **"Down Time per Device Type"** bar charts isolating outliers

### Key Findings
- **Osaka (Seiko)**: Highest failure rate (~480 Unhealthy units)
- **Shenzhen**: Second highest failure rate
- **LaserWelders & LaserCutters**: Primary drivers of global operational downtime

---

## Project 2: Forensic Gender Pay Equality Audit (Excel)

### Context
Forensic investigation auditing "level of gender pay equality" across global operations in response to internal complaints.

### Forensic Methodology
Implemented **"Equality class"** classification using nested IF statements based on **Equality Score** (-100 to +100):

| Classification | Score Range |
|----------------|-------------|
| **Fair** | -10 to +10 |
| **Unfair** | -20 to -10 OR +10 to +20 |
| **Highly Discriminative** | < -20 OR > +20 |

### Impact
Delivered prioritized roadmap for corporate intervention, pinpointing job roles and factory locations requiring immediate action.

---

## Repository Contents

- `Daikibo_Telemetry_Tableau_Dashboard.twb` — Interactive Tableau workbook quantifying global operational risk
- `Task_5_Equality_Table_Solution.xlsx` — Forensic audit with nested-logic pay equality classifications
- `daikibo-telemetry-data.json.zip` — Unified global telemetry logs for forensic analysis
