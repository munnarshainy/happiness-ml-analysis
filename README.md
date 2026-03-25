# Are Citizens of Asian Countries Happier Because of GDP, Generosity, or Dystopian Resilience?

**Author:** Munna R. Shainy
**Year:** 2025
[Find me on LinkedIn](https://www.linkedin.com/in/munnars)

---

## Project Overview

This project uses the **World Happiness Report 2025** dataset to investigate what drives happiness **across Asian countries**.

Using Python for data cleaning, visualization, and machine learning, I compared multiple models — **Linear Regression**, **Random Forest**, and **XGBoost** — to identify the key predictors of happiness scores and evaluate model performance.

---

## 🔍 Variables Considered

* **Log GDP per capita** — Proxy for economic well-being
* **Generosity** — Measure of prosocial behavior and willingness to help others
* **Dystopia + residual** — Captures structural and baseline societal conditions

---

## 🤖 Models Used

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

## Model Performance

| Model             | MAE   | R² Score |
| ----------------- | ----- | -------- |
| Linear Regression | 0.115 | 0.978    |
| Random Forest     | 0.552 | 0.449    |
| XGBoost           | 0.419 | 0.659    |

**Linear Regression achieved the highest performance**, suggesting a strong linear relationship between the selected features and happiness scores within the Asian subset.

---

## Key Insights

### 1. Economic strength dominates

* **Log GDP per capita** is the most influential predictor across all models.

### 2. Structural factors matter

* **Dystopia + residual** consistently ranks as the second most important feature, highlighting the role of societal stability and baseline conditions.

### 3. Generosity plays a smaller role

* While positively associated with happiness, **Generosity** shows a comparatively smaller effect size.

---

## Model Validation Insights

Feature importance was compared across **Linear Regression, Random Forest, and XGBoost**:

* Random Forest ranked **GDP highest**
* XGBoost ranked **Dystopia + residual highest**
* Generosity remained lowest across all models

This variation suggests that **nonlinear relationships and feature interactions may influence how structural and economic factors contribute to happiness**.

---

## Feature Importance (Summary)

| Feature             | Importance (RF) |
| ------------------- | --------------- |
| Log GDP per capita  | 0.518           |
| Dystopia + residual | 0.360           |
| Generosity          | 0.122           |

---

## Limitations

* Analysis is limited to **Asian countries**, and findings may not generalize globally
* Country-level aggregation may mask individual-level variation
* Limited feature set excludes factors like freedom, corruption perception, and mental health

---

## Future Directions

* Incorporate additional socio-political variables
* Explore **nonlinear modeling and interaction effects** in more depth
* Use **individual-level or longitudinal data** for stronger predictive insights
* Extend analysis to other global regions

---

## Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn, XGBoost

---

## Final Takeaway

> Economic prosperity is the strongest predictor of happiness across Asian countries, but structural societal conditions play a critical role — especially when nonlinear relationships are considered.

---
