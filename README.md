**# Predicting Blood Glucose Fluctuations Using Machine Learning**

## 📌 Project Overview

This project leverages **machine learning** to model and predict **blood glucose responses** based on dietary inputs, insulin activity, and lifestyle factors. Motivated by personal health concerns and growing public awareness around **Type 2 Diabetes**, the goal is to understand how **daily food choices** influence glucose spikes.

## 🧠 Motivation

My objective was to develop a machine learning tool to predict diabetes and improve early detection in Eritrean communities where diagnosis is often delayed. For this, I used the Pima Indians Diabetes Dataset, which provides medical features relevant to Type 2 diabetes prediction.

## 🔬 Project Details

- **Data Sources**: Public datasets (nutrition, glucose monitoring, insulin levels)
- **Diabetes Prediction**:
The dataset is primarily used to develop and test machine learning models for predicting whether an individual has diabetes based on medical features such as Glucose, BMI, Age, Pregnancies, BloodPressure, SkinThickness, Insulin, and DiabetesPedigreeFunction. The binary target (Outcome: 0 = non-diabetic, 1 = diabetic) makes it ideal for binary classification tasks.
Medical Research:
It provides insights into risk factors for diabetes, particularly among the Pima Indian population, which has a high prevalence of type 2 diabetes. Researchers use it to study correlations between features (e.g., high glucose or BMI) and diabetes onset.
Educational Tool:
The dataset is a staple in machine learning courses and tutorials due to its simplicity, small size (768 samples, 8 features), and real-world relevance. It’s used to teach concepts like data preprocessing, model training, evaluation, and feature engineering.
Algorithm Benchmarking:
Researchers and practitioners use it to compare the performance of different algorithms (e.g., SVM, Random Forest, Neural Networks) or techniques (e.g., feature scaling, hyperparameter tuning) on a standard dataset.
Data Preprocessing Practice:
The dataset contains challenges like zero values in biologically implausible features (e.g., Glucose, BMI), making it a good case study for handling missing or invalid data through imputation or other techniques.
Applications:

Building predictive models for early diabetes detection.
Developing healthcare tools for risk assessment.
Studying feature importance in diabetes risk (e.g., glucose levels or family history).
Testing new machine learning algorithms or preprocessing methods.
- **Technologies Used**:
  - Python (Pandas, Scikit-learn, Matplotlib)
  - Jupyter Notebook
- **Models Built**:
  - Linear Regression for glucose prediction
  - Random Forest and XGBoost for feature importance and better prediction accuracy
- **Target Output**:
  - Predict post-meal glucose levels
  - Visualize insulin responses
  - Track risk zones

## 📈 Key Outcomes

- Demonstrated **how food composition affects glucose spikes**
- Identified **high-risk combinations** using model insights
- Shared visualizations to raise awareness about **diet-related glucose changes**
- Inspired non-technical audiences to think about **preventive health**

## ✅ Results

- Achieved up to **85% prediction accuracy**
- Created clear **plots showing glucose fluctuations** with food inputs
- Used **feature importance scores** to highlight which nutrients impact glucose most

## 📎 How to Use

1. Clone the repository  
2. Run the Jupyter Notebook  
3. Input your own food data (or use the sample)  
4. View predicted glucose response and insights  

```bash
git clone https://github.com/your-username/glucose-predictor.git
