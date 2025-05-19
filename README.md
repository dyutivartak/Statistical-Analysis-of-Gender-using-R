# Gender Bias Analysis in University Faculty
Comprehensive statistical study using 1995 faculty data

---

## Project Overview
This repository presents a rigorous statistical assessment of gender bias in academia. Using faculty data from 1995, we test for disparities in representation, compensation, and career advancement between men and women.

### Hypothesis Tests Performed

| # | Test | Purpose |
|---|------|---------|
| 1 | Two‑Sample Z‑Test | Compare overall male vs. female faculty proportions |
| 2 | Two‑Sample Z‑Test | Analyze gender differences in hiring patterns |
| 3 | Welch’s t‑Test | Assess overall salary gap |
| 4 | Two‑Sample Z‑Test | Examine gender representation in senior positions |
| 5 | Welch’s t‑Test | Salary comparison at Assistant Professor level |
| 6 | Welch’s t‑Test | Salary comparison at senior ranks |
| 7 | Chi‑Square Test | Gender distribution across academic fields |
| 8 | Chi‑Square Test | Gender representation across academic ranks |

---

## Key Findings

* **Gender Imbalance** – Women comprised **25.6 %** of faculty, though **40.3 %** of new hires were female (p < 0.05).
* **Pay Gap** – Average salaries: **\$6,731** for men vs. **\$5,396** for women.
* **Promotion Disparity** – Assistant level nearly balanced (170 M / 145 F), but Full Professors were **719 M / 126 F**.
* **Field Clustering** – Women under‑represented in professional fields and over‑represented in “Other” disciplines.
* **Systemic Issues** – Consistent disparities across metrics signal entrenched structural bias.

---

## Data

The file `salary.txt` contains:

| Variable | Description |
|----------|-------------|
| case | Case ID |
| id | Faculty ID |
| sex | Gender (M / F) |
| deg | Degree type |
| yrdeg | Year degree earned |
| field | Academic field (Arts, Prof, Other) |
| startyr | Year hired |
| year | Current year |
| rank | Rank (Assist, Assoc, Full) |
| admin | Administrative duties (0 / 1) |
| salary | Annual salary |

---

## Analysis Workflow

1. Load & clean data  
2. Generate descriptive statistics  
3. Visualize key relationships (box plots, histograms, line & bar charts)  
4. Conduct hypothesis testing  
5. Interpret results and draw conclusions  

### Statistical Methods

* Z‑tests for proportions – representation differences  
* Welch’s t‑tests – mean salary comparisons with unequal variances  
* Chi‑square tests – independence between categorical variables  
* Logistic regression – time‑trend in hiring proportions  

---

## Visualizations

* Salary boxplots by gender  
* Salary histograms  
* Hiring‑trend line graphs (1990 – 1995)  
* Rank‑by‑gender bar charts  

---
