# Treatment Effects Using Block Designs

Statistical analysis of treatment effects in two experiments using block design methods.

---

## Project Summary

This project analyzes treatment effects in two real-world experiments using structured block designs. The first examines how poison and antidote combinations affect animal survival time. The second investigates how starter culture, batch, and position influence sour cream acidity.

---

## Objectives

- **Objective 1**: RCBD to assess effects of antidote and poison type on survival time, including interaction, polynomial trends, and power analysis
- **Objective 2**: Latin Square Design to examine effects of starter culture, batch, and position on sour cream acidity, including variance component estimation

---

## Key Results

- Both poison and antidote significantly affect survival time, with poison showing the stronger effect
- Blocking greatly reduced residual variance compared to a completely randomized design (*RE = 16.1*)
- Antidote 2 produced the highest survival time, while Antidote 1 produced the lowest
- Starter culture was the main factor influencing sour cream acidity, accounting for the largest variance component
- Position had little to no effect on acidity
---

## Visualizations

- Q–Q plots and Scale-Location plots for model diagnostics
- Cubic and linear polynomial trend plots for antidote effects
- ANOVA and Tukey HSD summary tables

---

## Tools & Libraries Used
**R (RStudio)**

### Libraries
- `lme4`
- `lsmeans`
- `car`
- `daewr`
- `dplyr`
- `knitr`
