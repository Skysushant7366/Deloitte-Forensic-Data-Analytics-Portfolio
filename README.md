Deloitte Forensic Data Analytics Portfolio
1. Professional Profile & Technical Narrative
I am a Forensic Data Analyst specializing in operational telemetry and corporate equity auditing, with a proven track record of distilling high-stakes business intelligence from fragmented data environments
. Upon completing the Deloitte Australia Data Analytics simulation, I demonstrated the ability to architect data solutions for Daikibo Industrials, transforming raw multi-level JSON schemas and complex Excel datasets into authoritative insights
. My expertise lies in bridging the gap between technical data engineering and executive-level decision-making through forensic investigation and advanced visualization
.

--------------------------------------------------------------------------------
2. Core Technical Competency Matrix
Category
Skills
Context
Data Engineering
Data Structures, Programming (Python), Computer Networking
Applied to understand the data unification algorithms used to synthesize global telemetry into a single JSON file
.
Analysis & Visualization
Tableau, Excel, Data Modeling, Spreadsheet Skills
Leveraged Tableau for multi-factory downtime modeling and Excel for forensic pay equality classification using nested logical functions
.
Operational Strategy
Log Analysis, Planning, Formal Communication
Interpreted 10-minute interval telemetry messages to identify failure patterns and synthesize findings for the Forensic Tech team
.

--------------------------------------------------------------------------------
3. Project 1: Daikibo Machine Telemetry Analysis (Tableau)
Context: The objective was to perform a large-scale analysis of operational telemetry for Daikibo Industrials to address critical machine reliability issues across four global manufacturing hubs: Tokyo (Meiyo), Osaka (Seiko), Berlin, and Shenzhen
.
Technical Execution & Methodology:
Schema Ingestion: Handled the daikibo-telemetry-data.json.zip file, performing decompression and import of multi-level JSON schemas to ensure all data hierarchies were preserved
.
Calculated Measure Engineering: Developed a custom "Unhealthy" status measure. This logic assigned a weight of 10 to every unhealthy status, representing 10 minutes of potential downtime since the preceding message
.
Visualization Architecture: Developed "Down Time per Factory" and "Down Time per Device Type" bar charts to isolate outliers
.
Quantitative Findings:
Osaka (Seiko) was identified as the factory with the highest failure rate (approx. 480 Unhealthy units), followed by Shenzhen
.
LaserWelders and LaserCutters were identified as the primary machine types driving operational downtime globally
.

--------------------------------------------------------------------------------
4. Project 2: Forensic Gender Pay Equality Audit (Excel)
Context: Conducted a forensic investigation to audit the "level of gender pay equality" across global operations in response to internal complaints regarding gender-based salary inequality
.
Forensic Methodology:
Nested Logic Classification: Implemented a forensic "Equality class" classification in Excel using nested IF statements to interpret the "Equality Score" (ranging from -100 to +100)
.
Classification Logic:
Fair: Score between -10 and +10
.
Unfair: (Score between -20 and -10) OR (Score between +10 and +20)
.
Highly Discriminative: Score < -20 OR Score > +20
.
Impact: Provided a prioritized roadmap for corporate intervention by pinpointing job roles and factory locations with the most severe pay gaps requiring immediate action
.

--------------------------------------------------------------------------------
5. Repository Contents
Daikibo_Telemetry_Tableau_Dashboard.twb: Interactive Tableau workbook quantifying global operational risk
.
Task_5_Equality_Table_Solution.xlsx: Forensic audit featuring nested-logic classifications for pay equality
.
daikibo-telemetry-data.json.zip: Unified global telemetry logs used for forensic analysis
.

--------------------------------------------------------------------------------
