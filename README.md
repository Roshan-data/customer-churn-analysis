# 📊 Customer Churn Prediction & Risk Segmentation

## 🚀 Project Overview
This project focuses on predicting customer churn in a telecom company using machine learning techniques. Customer churn means when customers stop using the service. The goal is to identify high-risk customers and help the company take action to reduce customer loss.

## 🎯 Objectives
- Analyze customer data and understand patterns
- Predict whether a customer will churn or not
- Identify key factors affecting churn
- Segment customers into risk categories (High, Medium, Low)
- Provide business recommendations

## 🧠 Machine Learning Models Used
- Logistic Regression
- Random Forest (Best Performing Model)
- Gradient Boosting

## ⚙️ Steps Performed

### 🔹 Task 1: Data Analysis
- Loaded dataset using Pandas
- Checked shape, data types, and preview
- Identified target variable (Churn)
- Checked class imbalance
- Handled missing values
- Performed statistical analysis
- Created correlation heatmap

### 🔹 Task 2: Data Preprocessing
- Converted TotalCharges to numeric
- Handled missing values using median
- Applied One-Hot Encoding for categorical data
- Created new features:
  - ChargesPerMonth
  - SeniorWithNoSupport
- Scaled numerical features using StandardScaler
- Split data into train and test sets

### 🔹 Task 3: Model Training & Evaluation
- Trained 3 models
- Evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
- Compared models using ROC curve
- Selected Random Forest as best model

### 🔹 Task 4: Risk Segmentation
- Used predicted probabilities
- Segmented customers into:
  - High Risk
  - Medium Risk
  - Low Risk

### 🔹 Task 5: Visualizations
- Feature importance chart
- Churn by contract type
- Tenure distribution
- Risk tier distribution
- Interactive Plotly scatter plot

## 📈 Key Insights
- Customers with month-to-month contracts are more likely to churn
- Customers with low tenure have higher churn risk
- Higher monthly charges increase churn probability
- High-risk customers are usually new customers with flexible plans

## 💡 Business Recommendations
- Encourage long-term contracts with discounts
- Focus on high-risk customers with personalized offers
- Improve customer support for better retention

## ⚠️ Limitations
- Does not include customer satisfaction data
- Dataset is slightly imbalanced
- Model can be improved with more features and tuning

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Plotly

## 📁 Project Structure
customer-churn-analysis/
│
├── analysis.ipynb
├── requirements.txt
├── summary.docx
├── model_comparison.png
├── scatter_plot.html
│
└── charts/
    ├── feature_importance.png
    ├── churn_by_contract.png
    ├── tenure_distribution.png
    ├── risk_tier_pie.png

## 👨‍💻 Author
Roshan Kumar  
B.Tech CSE (Data Analytics Enthusiast)

