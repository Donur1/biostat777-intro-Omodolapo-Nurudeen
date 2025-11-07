# Biostat 777 Intro — Omodolapo Nurudeen

**Author:** Omodolapo Nurudeen  
**Affiliation:** Ph.D. Student, Biomedical Engineering, Johns Hopkins University  
**Website:** [https://donur1.github.io/biostat777-intro-Omodolapo-Nurudeen/](https://donur1.github.io/biostat777-intro-Omodolapo-Nurudeen/)

---
This Quarto website was created as part of the **Biostatistics 777 — Statistical Programming** course.  

The website contains **three main pages**:
1. **Homepage (`index.qmd`)** — Introduction and research overview  
2. **About (`about.qmd`)** — Academic background, education, and research experience  
3. **Sample Analysis (`sample_analysis.qmd`)** — A mortality risk prediction analysis using NHANES 2003–2004 data  

---

## Dataset
The analysis uses data from the **National Health and Nutrition Examination Survey (NHANES 2003–2004)**, a U.S. population-based study that combines interviews and examinations to assess health and nutritional status.  Variables explored include demographic, clinical, and lifestyle factors to predict mortality among adults aged 40 and above.

Source: [CDC NHANES Database](https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Examination&CycleBeginYear=2003)

---

## ⚙️ Technical Details
- **Framework:** [Quarto](https://quarto.org/)  
- **Language:** R  
- **Packages Used:** `dplyr`, `ggplot2`, `tidyverse`, `MASS`, `caret`  
- **Deployment:** [GitHub Pages](https://pages.github.com/) via Quarto command  
  ```bash
  quarto render
  quarto publish gh-pages
