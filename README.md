# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict the **selling price of used cars** using Machine Learning techniques.  
Multiple models are trained and compared to identify the most accurate approach for price prediction.

---

## 🎯 Objectives
- Clean and preprocess raw data  
- Perform feature engineering  
- Train multiple regression models  
- Evaluate model performance  
- Select the best model for prediction  

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib  
- Scikit-learn  
- XGBoost  

---

## 📊 Models Used
- Linear Regression  
- Lasso Regression  
- Random Forest Regressor 🌳  
- XGBoost Regressor 🚀  

---

## ⚙️ Project Workflow

1. **Data Collection**

<img width="1455" height="877" alt="Screenshot 2026-04-08 162334" src="https://github.com/user-attachments/assets/f82a60a4-ebe6-4086-b367-eb1cc7b04934" />


2. **Data Cleaning**
   - Handling missing values  
   - Removing duplicates  

3. **Feature Engineering**
   - Extracting car brand from name  
   - Converting mileage, engine, max_power to numeric  

4. **Encoding**
   - One-hot encoding for categorical variables  

5. **Model Training**
   - Train-test split
   - Scaling (for linear models)

 <img width="1428" height="744" alt="Screenshot 2026-04-08 162431" src="https://github.com/user-attachments/assets/bbe7c52a-cced-4481-a084-090f1d3a3281" />


5. **Evaluation Metrics**
   - R² Score  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  

6. **Visualization**
   - Model comparison using bar charts  

<img width="1455" height="698" alt="Screenshot 2026-04-08 162515" src="https://github.com/user-attachments/assets/91acf9db-bbbb-4657-918c-1571bb885638" />

---

## 📈 Results

- **Random Forest and XGBoost performed the best**
- Achieved:
  - Higher R² Score  
  - Lower MAE and MSE  
- These models capture **non-linear relationships** effectively


---

## 🏁 Conclusion

Random Forest and XGBoost are the most suitable models for this dataset as they provide better accuracy and lower prediction error compared to linear models.

---


