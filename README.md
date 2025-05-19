# Medicaid Expansion & Non-Communicable Disease Outcomes (2010–2019)

**Team 32 – Duke MQM Capstone (Spring 2025)**  
**Client:** Duke Health | **Role:** Data Analyst  
**Repo Maintainer:** [Lizzie Wang](https://github.com/lizziewangliz)

---

## Project Overview

This project evaluates the impact of Medicaid expansion on non-communicable disease (NCD) outcomes across U.S. states. Taking advantage of the staggered adoption of Medicaid expansion under the Affordable Care Act (ACA), we use **causal inference techniques** to assess how access to care affected:

- **Deaths**
- **DALYs (Disability-Adjusted Life Years)**
- **Prevalence**
- **Incidence**

We focus on 10 high-burden NCDs using data from the **IHME Global Burden of Disease (GBD)** dataset (2010–2019).

---

## Research Questions

1. How did Medicaid expansion affect disease burden across different states?
2. Are outcomes significantly different in **Early**, **Mid**, or **Late** expansion states versus those that never expanded?
3. Which demographic groups saw the greatest health outcome shifts?

---


## Methodology

We used a two-step approach to uncover causal impacts:

### 1. **T-Test Filtering for Disease Selection**
- Compared pre- vs post-expansion periods (2010–2013 vs 2014–2019).
- Selected diseases with statistically significant changes (p < 0.05).

### 2. **Causal Inference: DiD and Fixed Effects**
- **Difference-in-Differences (DiD)**: Estimates treatment effect using treat_group × post interaction.
- **Fixed Effects Models**:
  - **State FE**: Controls for time-invariant differences across states.
  - **Year FE**: Adjusts for national policy/time shocks.

---

## Results Summary

### **Key Findings**
| Expansion Group | Impact | Notes |
|-----------------|--------|-------|
| **Early**       | Strongest improvement | Declines in DALYs, Deaths for CKD and Opioid disorders |
| **Mid**         | Mixed results | Only significant when year FE included |
| **Late**        | Minimal effect | Shorter post-expansion period limited results |

### **Demographic Insights**
- **Men** consistently showed higher Deaths and DALYs.
- **Older adults (50–69)** bore the highest burden.
- **Substance Use Disorders** had the steepest pre/post policy impact.

---

## Selected Diseases (N=10)

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

## My Contributions

As part of Team 32, I was responsible for:
- Writing R code for t-tests, data wrangling, and EDA visualizations
- Creating disease and demographic trend plots
- Interpreting causal models and generating policy insights

---

## License & Acknowledgments

This is a student-led academic project for Duke MQM. All data sourced from [IHME](https://www.healthdata.org/gbd).  
Special thanks to Duke Health and our faculty advisor.

---

## How to Navigate
- Read `/docs/Data Cleaning.docx` for prep methodology
- Explore `/scripts/Team 32 Capstone R Code.R` for full analysis workflow
- Check `Capstone Duke Health.pdf` for final insights

---

