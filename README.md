# Week 1 - Real-World ML Pipeline Project

This mini-project is part of Week 1 of the AMSS + Real-World ML series. The goal was to build a clean, modular, and production-ready ML pipeline using real-world tabular data.

## 📊 Project: Health Insurance Charge Prediction

We used the [Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) to predict medical charges based on features like age, BMI, smoking habits, and more.

---

## 🔧 ML Pipeline Components

- **Exploratory Data Analysis**
  - Histograms, boxplots, scatterplots
- **Feature Engineering**
  - Encoding categorical variables (One-Hot)
  - No missing values — clean data!
- **Model Training**
  - Linear Regression ✅
  - Random Forest Regressor ✅
- **Evaluation**
  - Metrics: Mean Squared Error, R² Score
  - Feature Importance Visualization

---

## 🧠 Key Insights

- **Smoking status** and **BMI** were major cost drivers
- Random Forest performed better than Linear Regression (R² ~ 0.86)

---

## 📁 Files

- `Week1_ML_Pipeline_HealthInsurance.ipynb`: Clean and commented notebook
- `README.md`: Project summary and structure

---

## ✅ Tools Used

- Python, Pandas, Scikit-learn, Seaborn, Matplotlib
- Jupyter Notebook / Google Colab

---

## 🚀 Next Steps

- Try hyperparameter tuning (GridSearchCV)
- Add train-test leakage checks
- Move code into functions/classes for modularity
