# Deloitte-Forensic-Data-Analytics-Portfolio
Forensic investigation into operational telemetry and corporate equity auditing for Daikibo Industrials
```markdown
# Deloitte Forensic Data Analytics Portfolio

## 1. Professional Profile & Technical Narrative
I am a Forensic Data Analyst specializing in operational telemetry and corporate equity auditing. This repository showcases my work for **Daikibo Industrials**, where I transformed raw, multi-level JSON schemas and complex Excel datasets into authoritative business intelligence. My expertise lies in bridging the gap between technical data engineering and executive-level decision-making through forensic investigation and advanced visualization.

---

## 2. Core Technical Competency Matrix
| Category | Skills |
| :--- | :--- |
| **Data Engineering** | Data Structures, JSON unification, handling multi-level schemas, and navigating networking logs. |
| **Analysis & Visualization** | Tableau (multi-factory downtime modeling) and Excel (forensic pay equality classification using nested logical functions). |
| **Operational Strategy** | Log analysis, identifying failure patterns from 10-minute interval telemetry, and synthesizing strategic findings. |

---

## 3. Project 1: Daikibo Machine Telemetry Analysis (Tableau)
**Objective:** Perform a large-scale analysis of operational telemetry to address critical machine reliability issues across four global manufacturing hubs: Tokyo (Meiyo), Osaka (Seiko), Berlin, and Shenzhen.

**Technical Execution:**
* **Schema Ingestion:** Processed the `daikibo-telemetry-data.json.zip` file, ensuring multi-level hierarchies were preserved during decompression.
* **Calculated Measure Engineering:** Developed a custom **"Unhealthy" status measure** using logic that assigned a weight of **10** to every unhealthy status, representing 10 minutes of potential downtime.
* **Visualization Architecture:** Created bar charts for "Down Time per Factory" and "Down Time per Device Type" to isolate outliers across 9 machine types.
* **Interactive Analytics:** Built a dynamic Dashboard where stakeholders can drill down into specific machine performance by location.

---

## 4. Project 2: Forensic Gender Pay Equality Audit (Excel)
**Objective:** Conducted a forensic investigation to audit gender-based salary inequality across global operations in response to internal complaints.

**Technical Methodology:**
* **Nested Logic Classification:** Implemented a tiered "Equality class" system in Excel using **nested IF statements** to interpret Equality Scores ranging from -100 to +100.
* **Classification Logic:**
    * **Fair:** Score between -10 and +10.
    * **Unfair:** Score between -20 to -10 OR +10 to +20.
    * **Highly Discriminative:** Score < -20 OR Score > +20.

**Impact:** Provided a prioritized roadmap for corporate intervention by pinpointing specific job roles and factories requiring immediate attention.

---

## 5. Repository Files
* `Daikibo_Telemetry_Tableau_Dashboard.twb`: The final interactive forensic tool for quantifying operational risk.
* `Task_5_Equality_Table_Solution.xlsx`: Forensic audit showing tiered gender pay classifications.
* `daikibo-telemetry-data.json.zip`: Unified telemetry logs used for global analysis.

---

*This project was completed as part of the Deloitte Australia Data Analytics Job Simulation on Forage.*
```
