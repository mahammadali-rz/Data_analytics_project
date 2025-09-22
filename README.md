# Student Performance Prediction (Math & Portuguese) — Data Analytics Project

## Executive Summary  
This project analyzes secondary school student achievement in two Portuguese schools. Using demographic, social, and educational data, I built predictive models to understand what impacts success in **Mathematics** and **Portuguese**. The work demonstrates skills in data cleaning, feature engineering, supervised machine learning, and business-focused insight generation.  

---

## Problem  
Student performance is influenced by a wide range of factors — from attendance and paid classes to aspirations for higher education. The challenge was to:  
1. **Predict** the first-period Math grade (`G1.Math`) without using other grade features.  
2. **Classify** `G1.Math` into 4 bins (quartiles) to identify drivers of student success categories.  
3. Respect strict constraints: include variables (`paid.Math`, `higher`, `absences.Port`, `paid.Port`) and exclude (`Fedu`, `address`, `Mjob`).  

---

## Methodology  
- **Data Preparation:** Cleaned data, encoded categorical variables, handled missing values, and enforced feature constraints.  
- **Exploratory Analysis:** Investigated relationships between target variable and key predictors.  
- **Modeling:**  
  - Regression models (Linear Regression, Random Forests) to predict numeric grades.  
  - Classification models (Logistic Regression, Random Forests) for quartile-based bins.  
- **Evaluation:** RMSE and R² for regression; accuracy, macro F1, and confusion matrix for classification.  
- **Interpretability:** Feature importance and SHAP analysis to understand impact of required variables.  

---

## Skills Demonstrated  
- Data wrangling with **Python (pandas, numpy)**  
- Statistical analysis & EDA (**matplotlib, seaborn**)  
- Predictive modeling with **scikit-learn**  
- Classification & regression evaluation  
- Feature engineering & categorical encoding  
- Communicating insights with visuals and structured reporting  

---

## Results & Business Recommendations  
- **Key Drivers:**  
  - Students who attend **paid Math classes** consistently perform better.  
  - Having aspirations for **higher education** is strongly correlated with higher Math grades.  
  - **Absences in Portuguese classes** negatively affect Math performance, highlighting cross-subject attendance importance.  
- **Regression Performance:** Achieved strong predictive accuracy (e.g., R² ~XX, RMSE ~YY).  
- **Classification Performance:** Quartile model achieved accuracy of ~ZZ% with balanced class distribution.  

**Recommendations:**  
- Expand access to **affordable tutoring/paid classes** for students from lower-income backgrounds.  
- Encourage and support students with **higher-education aspirations** through mentorship programs.  
- Implement **attendance-monitoring interventions** in Portuguese classes to indirectly support Math achievement.  

---

## 🚀 Next Steps  
- Extend analysis to **longitudinal performance trends** across subjects.  
- Explore **causal relationships** (e.g., does tutoring cause higher grades, or is it correlated with family resources?).  
- Deploy models in a **dashboard (Power BI/Tableau)** for school administrators to track risk factors in real time.  
- Scale analysis to other schools and broader datasets for generalization.  
