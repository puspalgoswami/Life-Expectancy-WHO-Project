Here's a detailed and structured **README.md** section for your **Life Expectancy Prediction using WHO Dataset** project. You can paste this into your GitHub repository:

---

# 🌍 Life Expectancy Prediction using WHO Dataset

This project focuses on predicting **life expectancy** based on various socio-economic and health-related features using machine learning techniques. The dataset was sourced from the **World Health Organization (WHO)**, and models were trained to analyze and forecast the life expectancy of different countries over several years.

---

## 📁 Dataset Overview

The dataset includes 22 features such as:

* Adult Mortality
* Infant Deaths
* Alcohol Consumption
* Percentage Expenditure on Healthcare
* Hepatitis B Immunization Rate
* BMI
* Under-Five Deaths
* GDP
* Schooling, etc.

The target variable is:

* **Life expectancy (years)**

---

## 🎯 Project Objectives

* Explore and clean the WHO dataset
* Perform **EDA** (Exploratory Data Analysis)
* Handle missing values and outliers
* Train and evaluate multiple regression models
* Select the best model based on performance metrics

---

## 🧠 Machine Learning Models Used

The following models were implemented and evaluated:

1. **Linear Regression**
2. **Random Forest Regressor**
3. **XGBoost Regressor**

---

## 🧪 Evaluation Metrics

Each model was evaluated using:

* **R² Score**
* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**

---

## ✅ Best Performing Model

* **Random Forest Regressor** delivered the best results in terms of accuracy and generalization.
* It handled both non-linear relationships and missing data effectively.

---

## 📊 Visualization & Insights

* Correlation Heatmaps
* Feature Importance plots
* Actual vs Predicted Graphs
* Distribution and trend plots for features like Schooling, GDP, Adult Mortality

---

## 🧱 Libraries Used

* `pandas`, `numpy`
* `matplotlib`, `seaborn`
* `sklearn`
* `xgboost`

---

## 📌 Challenges Faced

* Dealing with missing values in features like `BMI`, `GDP`, and `Schooling`
* Choosing appropriate regression models
* Avoiding overfitting
* Selecting optimal hyperparameters

---

## 📁 Folder Structure

```
life-expectancy-prediction/
├── data/
│   └── Life Expectancy Data.csv
├── notebooks/
│   └── life_expectancy_analysis.ipynb
├── plots/
│   └── feature_importance.png
│   └── actual_vs_predicted.png
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

   ```
   git clone https://github.com/yourusername/life-expectancy-prediction.git
   cd life-expectancy-prediction
   ```

2. Install dependencies

   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook

   ```
   jupyter notebook notebooks/life_expectancy_analysis.ipynb
   ```

---

## 📌 What I Learned

* Handling real-world datasets with missing and inconsistent data
* Comparing and tuning regression models
* Interpreting model performance using evaluation metrics
* Visual storytelling using matplotlib

---

## 📬 Contact

Made with ❤️ by **Puspal Goswami**
📧 Email: \[[goswamipuspal2005@gmail.com ](mailto:goswamipuspal2005@gmail.com)]
🔗 Portfolio: \[[puspalgoswami.github.io/Portfolio](https://puspalgoswami.github.io/Portfolio/
)]

---

Let me know if you'd like a shorter or lighter version, or if you want the GitHub description section too.
