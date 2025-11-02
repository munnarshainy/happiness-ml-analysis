# Are Citizens of Asian Countries Happier Because of GDP, Generosity, or Dystopian Resilience?  

**Author:** Munna R. Shainy  
**Year:** 2025  
[Find me on LinkedIn](https://www.linkedin.com/in/munna-rs)

---

This project uses the **World Happiness Report 2025** dataset ([source](https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated)) to explore what really drives happiness across Asian countries.  

Using Python for data cleaning, visualization, and machine learning, I compared three models — **Linear Regression**, **Random Forest**, and **XGBoost** — to identify which factors best predict happiness scores.

---

### Variables Considered
- **Log GDP per capita:** Represents economic well-being.  
- **Generosity:** Measures willingness to donate and help others.  
- **Dystopia + residual:** A benchmark score ensuring no country has a happiness score lower than the hypothetical “Dystopia.”

---

### Models Used
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

Random Forest achieved the best performance with an **R² ≈ 0.50**, indicating a moderate ability to explain variance in happiness scores.

---

### 🧠 Interpreting Results
Although the feature importance values are relatively modest (likely due to a smaller sample size), the Random Forest analysis offers meaningful insights:

- **Economic well-being (Log GDP per capita)** remains the strongest predictor of happiness.  
- **Social and moral dimensions (Generosity and Dystopia + residual)** contribute as secondary influences, reflecting community and perceived well-being.  
- Overall, while financial prosperity plays a major role in happiness, underlying social trust and emotional resilience serve as essential complements.

---

### Tech Stack
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost  

---

### 📊 Results Summary
| Feature                | Importance |
|------------------------|-------------|
| Log GDP per capita     | 0.518       |
| Dystopia + residual    | 0.360       |
| Generosity             | 0.122       |

---

### 💡 Future Directions
- Explore individual-level data for better prediction power.  
- Include additional variables (e.g., freedom, corruption perception).  
- Test model generalization across other regions.

---
