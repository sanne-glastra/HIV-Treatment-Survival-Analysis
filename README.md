# HIV Treatment Survival Analysis
Comparative survival analysis (Kaplan-Meier, Cox Proportional Hazards) of HIV treatment regimens using R.

![Status](https://img.shields.io/badge/Status-Completed-success)
![R](https://img.shields.io/badge/Language-R-blue)

## 📌 Project Overview
This study performs a survival analysis to evaluate the efficacy of a three-drug regimen (containing Indinavir) versus a standard two-drug regimen. Using clinical trial data from 1,151 subjects, the analysis assesses two primary outcomes:
1.  **Progression-Free Survival (PFS):** Time to AIDS diagnosis or death.
2.  **Overall Survival (OS):** Time to all-cause death.

## 🔍 Key Findings
* **Treatment Efficacy:** The three-drug regimen reduced the risk of progression and death by approximately **50%** (HR: 0.50, p=0.001) compared to the two-drug standard.
* **Predictors:** Higher Karnofsky performance scores and baseline CD4 counts were strongly associated with better outcomes.

## 🛠️ Methodology
* **Language:** R (v4.4.1)
* **Techniques:** Kaplan-Meier Estimation, Log-Rank Tests, Cox Proportional Hazards Models (Univariate & Multivariate).
* **Libraries:** `survival`, `ggsurvfit`, `tidyverse`, `flextable`.

## 📄 Full Report
You can view the full interactive code and analysis [here](https://sanneglastra.github.io/HIV-Treatment-Survival-Analysis/).
*(Note: This link will work after you complete Phase 4 below)*.
