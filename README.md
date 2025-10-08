# 🛳️ Titanic Survival Analysis & Prediction

**Author:** Arame Tanor Deme  
**Focus:** Data Analytics • Predictive Modeling • Visualization  
**Stack:** Python • Pandas • Matplotlib • Scikit-learn • Google Colab

---

## 🎯 Overview
This project explores the Titanic dataset to understand which factors influenced survival and builds a logistic regression model to predict whether a passenger survived. It demonstrates the full analytics pipeline—from cleaning and feature engineering to visualization and model evaluation.

---

## ⚙️ Pipeline
- **Import & Clean**: Handle missing values; standardize key fields.
- **Feature Engineering**: `SexNum`, `FamilySize`, `IsAlone`, `AgeBand`, `Embarked` dummies.
- **EDA**: Survival distributions and segmented survival rates.
- **Modeling**: Logistic Regression to predict `Survived`.
- **Evaluation**: Accuracy, ROC AUC, and Confusion Matrix.

---

## 📊 Key Visuals

### Survival Distribution
![Survival Pie](./survival_pie.png)

### Survival Rate by Sex
![Survival by Sex](./survival_by_sex.png)

### Survival Rate by Passenger Class
![Survival by Class](./survival_by_pclass.png)

### Survival Rate by Age Band
![Survival by Age Band](./survival_by_ageband.png)

### Confusion Matrix (Model Evaluation)
![Confusion Matrix](./confusion_matrix.png)

---

## 🧠 Model Performance
- **Accuracy:** 0.785  
- **ROC AUC:** 0.848

**Confusion Matrix:**
```
[[115  22]
 [ 26  60]]
```

**Interpretation:**
- **True Positives**: Correctly predicted survivors
- **True Negatives**: Correctly predicted non-survivors
- **False Positives**: Predicted survival but passenger did not survive
- **False Negatives**: Missed actual survivors

---

## 🚀 Next Steps
- Compare with **Random Forest** or **XGBoost**
- Add cross-validation and hyperparameter tuning
- Build a **Tableau dashboard** for storytelling
- Package as a **Streamlit app**

---


---

## ✨ Author
**Arame Tanor Deme**  
Energy Engineer → Data Analytics  
LinkedIn: https://www.linkedin.com/in/arametd  
Email: demearame@gmail.com
