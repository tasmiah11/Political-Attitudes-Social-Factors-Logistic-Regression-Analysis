
# 🧠 Logistic Regression Project – Political & Social Influence on Abortion Opinions
This R Markdown project analyzes how students' social, political, and personal beliefs influence their stance on abortion (abor) using logistic regression. The dataset includes both numerical and categorical predictors like ideology, life values, and religious beliefs.
This R Markdown project explores how various personal, religious, and political attributes affect a student's opinion on abortion using logistic regression.

---

## 📦 Dataset

- Source: `Students.dat`
- Variables include: `gender`, `age`, `ideol` (ideology), `relig` (religious belief), `affirm`, `life`, `veg`, `aids`, and more

---

## 🔍 Key Activities

### 1. Data Cleaning & Preparation
- Handled missing values
- Converted categorical variables to factors
- Identified numeric predictors

### 2. Outlier Detection
- Visualized numeric variables using boxplots
- Detected and counted outliers via IQR method

### 3. Model Building & Selection
- Fitted a full logistic regression model: `abor ~ all predictors`
- Built reduced models via:
  - Backward elimination
  - Purposeful selection

### 4. Evaluation & Diagnostics
- Compared models with ANOVA
- ROC curve analysis and classification accuracy
- Odds ratio interpretation and CI analysis

---

## 📊 Output Metrics

- Model significance via p-values
- AUC for model strength
- Classification table for predictive accuracy

---

## 🧰 Tools & Libraries

- `dplyr` for data wrangling
- `ggplot2` for visualization
- Base R for modeling
- `car` and `pROC` for diagnostics

---

## 🧠 Insights

This analysis demonstrates how personal and political beliefs statistically influence abortion opinions, highlighting key predictors with strong explanatory power.

---
