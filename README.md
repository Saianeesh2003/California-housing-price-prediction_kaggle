# California-housing-price-prediction_kaggle
A Machine Learning project that predicts median house values in California using the famous Housing dataset.  

## 📌 Project Overview
The goal is to build a regression model that predicts house prices based on:
- Median income  
- Housing age  
- Total rooms and bedrooms  
- Population and households  
- Latitude & longitude  
- Ocean proximity (categorical)


## 📂 Dataset
The dataset used is `housing.csv`, containing 20,640 rows and 10+ features.


## 🔧 Technologies Used
- Python  
- Pandas  
- NumPy   
- Scikit-Learn  
- Jupyter Notebook  


## 🚀 Workflow
### **1. Data Cleaning**
- Handled missing values in `total_bedrooms` using median
- Verified dataset has no NaN after cleaning

### **2. Feature Engineering**
- One-hot encoded `ocean_proximity`
- Scaled numerical features using `StandardScaler`

### **3. Model Training**
Model used:
- **Linear Regression**

Train-Test Split: `70% train / 30% test`

### **4. Model Evaluation**
- **R² Score:** ~0.639  
- **RMSE:** ~68,800  


## 📈 Results
The model explains around **64%** of price variance and gives an average error of **$68k**.

This is a strong baseline model.  
Improvements can be done using:
- Random Forest Regressor  
- Gradient Boosting  
- Hyperparameter tuning  
- Polynomial features  
- Log transform on skewed variables  

Contributions
Open to suggestions, improvements, or pull requests!

📜 License
This project is for educational purposes.

