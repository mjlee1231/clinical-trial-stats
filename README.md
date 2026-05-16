# Clinical Trial Statistics

A personal study archive on biostatistics methods used in clinical trials.

---

## Topics

| # | Topic | Key Concepts |
|---|-------|-------------|
| 01 | [Estimand Framework](./01-estimand/estimand.qmd) | ICH E9(R1), intercurrent events, ITT/PP |
| 02 | [Survival Analysis](./02-survival-analysis/survival.qmd) | KM, log-rank, Cox PH, PH assumption |
| 03 | [MMRM](./03-mmrm/mmrm.qmd) | Mixed model, repeated measures, ANCOVA vs MMRM |
| 04 | [Missing Data](./04-missing-data/missing_data.qmd) | MCAR/MAR/MNAR, multiple imputation, sensitivity analysis |
| 05 | [Multiple Testing](./05-multiple-testing/multiple_testing.qmd) | FWER, FDR, Bonferroni, graphical approach |
| 06 | [Interim Analysis](./06-interim-analysis/interim_analysis.qmd) | Alpha spending, O'Brien-Fleming, DSMB |
| 07 | [Sample Size & Power](./07-sample-size/sample_size.qmd) | Power calculation, assumptions, re-estimation |
| 08 | [Regulatory & Docs](./08-regulatory/regulatory.qmd) | SAP, CDISC, ICH E3/E6/E9, CSR |

---

## Key References

| Document | Content | Link |
|----------|---------|------|
| ICH E9 | Statistical Principles for Clinical Trials | [FDA](https://www.fda.gov/media/71336/download) |
| ICH E9(R1) | Estimand Addendum | [ICH](https://www.ich.org/page/efficacy-guidelines) |
| ICH E3 | CSR Structure & Content | [ICH](https://www.ich.org/page/efficacy-guidelines) |
| ICH E6(R2) | GCP | [ICH](https://www.ich.org/page/efficacy-guidelines) |

---

## Environment

```r
library(survival)   # Survival analysis
library(survminer)  # KM plots
library(mmrm)       # MMRM
library(mice)       # Multiple imputation
library(gMCP)       # Graphical multiple testing
library(gsDesign)   # Group sequential design
```
