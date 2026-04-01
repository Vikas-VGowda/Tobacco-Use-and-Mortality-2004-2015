# Tobacco Data Analysis & Smoking Mortality Prediction

## Project Overview

Smoking is a major public health concern worldwide, contributing to deaths, hospital admissions, and long-term health complications. This project performs an end-to-end data analysis and machine learning workflow to understand smoking trends, economic influences, and predict high mortality outcomes.

The project integrates multiple datasets related to smoking deaths, hospital admissions, tobacco economics, prescriptions, and smoker prevalence. It combines data cleaning, exploratory data analysis (EDA), visualization, and machine learning to generate meaningful public health insights.

---

## Objectives

- Analyze trends in smoking-related deaths and hospital admissions over time  
- Study the impact of economic factors like tobacco price and affordability  
- Understand smoker prevalence patterns  
- Explore relationships between key features and mortality  
- Build a machine learning model to predict high mortality cases  
- Generate actionable public health insights  

---

## Dataset

**Sources:** Multiple datasets merged  
- Fatalities (smoking deaths)  
- Hospital admissions  
- Tobacco economic metrics  
- Pharmacotherapy prescriptions  
- Smoker prevalence  

**Time Period:** 2004 – 2014  

**Key Features:**
- Year, Sex  
- Smoking deaths  
- Hospital admissions  
- Smoker percentage  
- Tobacco Price Index  
- Affordability of Tobacco Index  
- Tobacco expenditure percentage  
- Pharmacotherapy prescriptions  

**Target Variable:**  
- `high_mortality` (1 = high smoking deaths, 0 = low)

---

## Exploratory Data Analysis (EDA)

### Key insights:

- Smoking-related deaths and hospital admissions show a declining trend over time  
- Male population consistently shows higher deaths and admissions than females  
- Smoker prevalence has decreased, indicating improved awareness and control  
- Tobacco prices have increased, while affordability has decreased  
- Pharmacotherapy prescriptions have increased, indicating rising quitting attempts  
- Strong relationships exist between smoker prevalence, affordability, and deaths  

EDA was supported with visualizations including line plots, heatmaps, and scatter plots with business-focused interpretations.

---

## Machine Learning Approach

### Models Implemented

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)  
- Gradient Boosting  
- XGBoost  
- LightGBM  

---

### Key Techniques

- Data cleaning and merging multiple datasets  
- Handling missing values  
- Feature engineering (mortality classification, scaling)  
- Feature selection using correlation analysis  
- Standardization using StandardScaler  
- Train-test split for model evaluation  

---

## Model Performance

- Tree-based models (Random Forest, XGBoost, LightGBM) performed best  
- Logistic Regression provided a good baseline  
- Ensemble models showed better accuracy and generalization  
- Models effectively classified high vs low mortality cases  

---

## Feature Importance

Key factors influencing smoking mortality:

- Smoker prevalence → Strongest predictor of deaths  
- Affordability of tobacco → Higher affordability leads to higher deaths  
- Tobacco price index → Impacts consumption patterns  
- Pharmacotherapy prescriptions → Indicates quitting efforts  
- Hospital admissions → Closely linked with mortality  

These features are critical in predicting and understanding smoking-related risks.

---

## Business Usage

This project can help governments, healthcare organizations, and policymakers to:

- Predict high-risk populations for smoking-related deaths  
- Design effective anti-smoking policies  
- Optimize taxation strategies on tobacco products  
- Promote smoking cessation programs  
- Allocate healthcare resources efficiently  

---

## Limitations

- Based on historical data (2004–2014), not real-time  
- Limited behavioral and demographic features  
- Does not include external factors like marketing or policy changes  
- Predictions support decision-making but should not replace expert judgment  

---

## Repository Contents

- `Tobacco.ipynb` → Complete analysis and machine learning workflow  
- `fatalities.csv` → Smoking deaths data  
- `admissions.csv` → Hospital admissions data  
- `metrics.csv` → Economic indicators  
- `prescriptions.csv` → Smoking cessation prescriptions  
- `smokers.csv` → Smoker prevalence data  
- `README.md` → Project documentation  

---

## Author

**Vikas Gowda V**  
Aspiring Data Analyst / Data Scientist  

---

## Conclusion

This project demonstrates a comprehensive data analysis and machine learning workflow focused on smoking-related public health data. By combining trend analysis, economic insights, and predictive modeling, it highlights key factors influencing smoking mortality and supports data-driven policy and healthcare decisions.
