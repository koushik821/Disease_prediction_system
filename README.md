# Disease Prediction System â€” Week 3: EDA & Visualization Strategy

Week 3 deliverable for the **Virtual Data Science Apprentice â€“ Python Specialist Intern** program (NSDC YuvaIntern). This week sets out the exploratory data analysis and visualization strategy applied to the cleaned dataset.

> âš ï¸ **Disclaimer:** Educational/portfolio project only â€” not a medical diagnostic tool.

## Objective
Explore feature distributions, class balance, and feature-target relationships to surface insights that will guide model selection in Week 4.

## Contents
```
week3-eda/
â”œâ”€â”€ Week3_EDA_Visualization_Strategy.docx   # Full EDA & visualization plan
â””â”€â”€ README.md
```

## What's in the Report
- Univariate analysis: histograms + KDE, box plots (numeric features); count plots (categorical features)
- Bivariate/multivariate analysis: grouped box plots and bar charts of features vs. disease outcome
- Correlation heatmap to flag multicollinearity
- Pair plot (curated feature subset) colored by target class
- Class balance check on the target variable
- A visualization-to-insight mapping table tying each plot to a specific downstream modelling decision
- Domain hypotheses to validate (e.g., age and cholesterol vs. risk, max heart rate inverse relationship)
- 7-step implementation plan for generating and documenting plots

## Tools
`pandas`, `matplotlib`, `seaborn`

## Depends On
Week 2 cleaned and transformed dataset.

## Next Step
Week 4 will use these insights to inform model selection and feature importance interpretation.

## Author
[Your Name] â€” Virtual Data Science Apprentice, NSDC YuvaIntern
