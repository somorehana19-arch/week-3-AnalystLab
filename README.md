# Hospital Operations, Cost & Patient Flow Intelligence
**AnalystLab Africa Experience Lab — Week 3 (Track B: Data Science)**

## 1. Project Overview
This project investigates hospital operations, encounter claim costs, payer coverage gaps, clinical procedure utilization, and 30-day repeat visit patterns across **12,749 hospital encounters** and **14,009 procedures** for **842 active patients** at Massachusetts General Hospital (2011–2016).

The objective is to move beyond descriptive summaries by applying rigorous exploratory data analysis (EDA) and non-parametric statistical hypothesis testing to support evidence-based capacity planning, financial risk management, and care-coordination decisions.

---

## 2. Repository Structure
```text
AnalystLab_Week3/
├── week3_data_science_analysis.ipynb   # Reproducible Jupyter Notebook (EDA, hypothesis tests, figures)
├── README.md                           # Project documentation & reproduction instructions
├── fig1_encounter_volumes.png          # Annual encounter volume by encounter class (2011–2016)
├── fig2_cost_by_class.png              # Total claim cost distribution across encounter classes (log scale)
├── fig3_duration_vs_cost.png           # Encounter duration vs. total claim cost (log-log scale)
├── fig4_cost_by_payer.png              # Mean vs. median total claim cost by payer
├── fig5_top_procedures.png             # Top 10 most frequently performed clinical procedures
├── hospital_analytics_questions.sql    # Reference SQL validation queries
├── create_hospital_db.sql              # Isolated database schema & setup script
├── data_dictionary.csv                 # Field definitions and schema reference
├── encounters.csv                      # Encounter-level records (12,749 rows)
├── patients.csv                        # Patient demographics (974 rows; PII excluded from outputs)
├── procedures.csv                      # Procedure-level records (14,009 rows)
├── payers.csv                          # Insurance payer directory (10 rows)
└── organizations.csv                   # Facility metadata (Massachusetts General Hospital)
