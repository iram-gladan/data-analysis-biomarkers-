# Data Analysis Biomarkers
This is an edit I am making for practice. 

# Biomarkers (OVT/CALP) vs Coccidiosis Lesions

This project analyzes whether two inflammatory biomarkers — Ovotransferrin (OVT) and Calprotectin (CALP) — are associated with coccidiosis lesion scores, with a focus on Eimeria tenella lesion severity.

It includes:
- Data loading and cleaning from an Excel file
- Numeric conversion for European decimal formatting (e.g., `"1,5"` → `1.5`)
- Log10 transformation of biomarkers
- Ordinal regression models (diagnostic perspective): do biomarkers predict higher lesion scores?
- Linear models (biological perspective): which lesion scores and factors explain biomarker variation?
- Basic diagnostic checks and two jitter plots for interpretation
- To download the script via Github:
git clone <git@github.com:iram-gladan/data-analysis-biomarkers-.git>
- Project structure: 
data-analysis-biomarkers-/
│
├── biomarkers_ovt_calp_vs_lesions.R   # Main analysis script
├── 20260203_biomarker_ls.xlsx         # Input dataset
└── README.md


---

## Requirements

- R (recommended: R 4.2+)
- R packages:
  - `readxl`
  - `dplyr`
  - `janitor`
  - `stringr`
  - `MASS`
  - `ggplot2`
  - `here`

Install packages in R:

```r
install.packages(c("readxl","dplyr","janitor","stringr","MASS","ggplot2","here"))


 
 