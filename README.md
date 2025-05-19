# Medicaid Expansion & Non-Communicable Disease Outcomes

**Type:** Capstone Team Project  
**Client:** Duke Health  
**Tools:** R, ggplot2, dplyr, Difference-in-Differences, Fixed Effects Models  
**Timeline:** Spring 2025  
**My Role:** Data Analyst – Causal Inference & Visualization

---

## Overview

This project explores how Medicaid expansion under the ACA impacted non-communicable disease (NCD) outcomes across U.S. states. Using a natural experiment framework from staggered expansion timing (Early, Mid, Late, Never), we assessed how access to care affected four outcomes:  
- **Deaths**  
- **DALYs (Disability-Adjusted Life Years)**  
- **Prevalence**  
- **Incidence**

---

## Project Structure

- `Data Cleaning.docx` – Preprocessing strategy and selection logic
- `Team 32 Capstone R Code.R` – Clean, modular R scripts for:
  - EDA & visualizations
  - t-test-based disease selection
  - Difference-in-Differences and Fixed Effects modeling
- `Capstone Duke Health.pdf` – Final presentation with findings
- `Final Deliverables Guide.docx` – Guide to project artifacts

---

## My Contributions
- Cleaned and reshaped multi-source health data (~120K observations)
- Wrote custom R functions for t-tests, disease filtering, and visual analysis
- Visualized disease trends by year, sex, and age group
- Conducted causal inference using DiD & FE models to evaluate policy effects

---

## Key Findings
- Early-expansion states saw significant **reductions** in deaths and DALYs from kidney disease, opioid use, and substance abuse
- Mid- and Late-expansion states showed mixed or lagged effects
- **Year fixed effects** were critical for identifying robust policy-driven improvements
- Most disease burden was concentrated in adults aged 50–69

---

## Selected Diseases (Top 10 NCDs)
1. Substance use disorders  
2. Drug use disorders  
3. Opioid use disorders  
4. Diabetes & kidney diseases  
5. CKD due to diabetes  
6. CKD due to hypertension  
7. Chronic kidney disease  
8. Alzheimer’s disease  
9. Alcohol use disorders  
10. Uterine cancer

---

## Technologies & Skills
- R (data cleaning, t-tests, panel models, ggplot2)
- Policy evaluation methods: DiD, fixed effects
- GitHub project documentation

---

## Lessons Learned
- Data cleaning across 16 CSVs taught me to modularize code and automate validation  
- Fixed effects models revealed the importance of controlling for national trends  
- Visual storytelling was key for stakeholder communication with Duke Health

---

## Team Acknowledgment
This was a team project for Duke MQM’s capstone. Teammates included:
- Richard Xie, Danielle Dawazhuoma, Shrishti Agarwal, Utkarsh Gupta, Lizzie Wang  
Special thanks to our faculty advisor and Duke Health for their guidance.
