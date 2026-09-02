# Disease Prediction System â€” Week 4: ML Model Selection & Evaluation

Week 4 deliverable for the **Virtual Data Science Apprentice â€“ Python Specialist Intern** program (NSDC YuvaIntern). This is the final week, covering model selection, training, and evaluation.

> âš ï¸ **Disclaimer:** Educational/portfolio project only â€” not a medical diagnostic tool.

## Objective
Select, train, and evaluate classification models to predict heart disease risk, and choose a final model balancing performance and interpretability.

## Contents
```
week4-modeling/
â”œâ”€â”€ Week4_ML_Model_Selection_Evaluation.docx   # Full model selection & evaluation plan
â””â”€â”€ README.md
```

## What's in the Report
- Candidate models compared: Logistic Regression, Decision Tree, Random Forest, SVM, KNN
- Model selection criteria: performance, interpretability, robustness, compute cost, scaling sensitivity
- Evaluation metrics: accuracy, precision, recall, F1, ROC-AUC, confusion matrix â€” with **recall weighted heavily** given the cost of missing an at-risk patient
- Validation strategy: 80/20 stratified split, 5-fold stratified cross-validation, `GridSearchCV` tuning, single untouched final test evaluation
- 8-step process from baseline model through final selection and feature-importance analysis
- Trade-off table (e.g., Random Forest performance vs. Logistic Regression interpretability)
- Deliverables: comparison table, final model with justification, feature importance summary, limitations discussion

## Tools
`scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `SVC`, `KNeighborsClassifier`, `GridSearchCV`, metrics module)

## Depends On
Week 2 cleaned dataset and Week 3 EDA insights.

## Outcome
Final selected model with a documented, metric-driven justification â€” completing the 4-week Disease Prediction System project.

## Author
[Your Name] â€” Virtual Data Science Apprentice, NSDC YuvaIntern
