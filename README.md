# 🚗 CarDekho Used Car Price Prediction

## 🛠️ Technologies Used
- **Data Cleaning**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization**
- **Machine Learning**

## 🌐 Domain
**Automobile Industry**

---

## 🧠 Problem Statement
The primary objective of this project is to develop a data science solution for accurately predicting used car prices.  
By analyzing a diverse dataset—including car model, number of owners, age, mileage, fuel type, kilometers driven, features, and location—we aim to build a machine learning model that provides current valuations for used cars.

---

## 📊 Data Understanding
The dataset consists of multiple Excel files, each representing a different city.  
Each file provides details, specifications, and available features of various cars.  

**Data Source:** [CarDekho Dataset](https://drive.google.com/drive/folders/14GXrGlaXzys0qybbG4DfeolnPApcX5tZ)  

**Feature Description:** Available on the 3rd page of the dataset.

---

## 🚀 Project Approach

### 1️⃣ Data Import  
- Import data from all Excel files representing different cities.  
- Combine datasets into a unified DataFrame for analysis.  

### 2️⃣ Data Exploration  
- Examine dataset structure.  
- Identify missing values, outliers, data types, and distributions.  
- Perform initial statistical analysis to understand relationships.  

### 3️⃣ Data Preprocessing  
- Handle Missing Values: Impute or remove missing values appropriately.  
- **Feature Engineering:**  
  - Extract useful information like car age, mileage, and derived features.  
- **Encoding Categorical Variables:**  
  - Apply techniques like One-Hot Encoding or Label Encoding.  
- **Normalization/Scaling:**  
  - Scale numerical features to ensure comparability.  

### 4️⃣ Exploratory Data Analysis (EDA)  
- Visualize feature distributions and relationships.  
- Identify trends and insights for better model performance.  
- Analyze correlations with the target variable (price).  

### 5️⃣ Model Selection  
- Select appropriate regression models for predicting continuous target variables.  
- Models considered:  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
  - XGBoost Regressor  

### 6️⃣ Model Evaluation  
- Evaluate models using performance metrics like:  
  - **Mean Absolute Error (MAE)**  
  - **Mean Squared Error (MSE)**  
  - **R-squared (R²)**  

### 7️⃣ Model Optimization  
- Perform hyperparameter tuning using Grid Search or Randomized Search.  
- Improve model performance through iterative experimentation.  

### 8️⃣ Feature Importance  
- Analyze the importance of various features to identify key predictors.  
- Use techniques like SHAP values or model coefficients.  

---

## 🔍 Insights & Results  
- Identify key factors affecting used car prices.  
- Develop an interactive tool or report to communicate insights.  
- Provide actionable recommendations based on analysis outcomes.  

---

## 📂 Project Structure
```plaintext
├── data/                   # Raw dataset files (Excel files per city)
├── notebooks/              # Jupyter Notebooks for analysis
├── src/                    # Python scripts for data processing and modeling
├── models/                 # Saved machine learning models
├── visualizations/         # EDA and model performance visualizations
├── README.md               # Project documentation
└── requirements.txt        # Required Python libraries
