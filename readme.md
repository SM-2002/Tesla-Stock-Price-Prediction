# 📈 Tesla Stock Price Prediction using Machine Learning

## 📌 Overview
This project builds a predictive machine learning model to forecast the stock prices of **Tesla** using its historical stock market data.  
It demonstrates the complete ML pipeline — from data preprocessing and feature scaling to model building, evaluation, and serialization for deployment.

---

## ⚙️ Features
- Preprocessed and cleaned historical Tesla stock data  
- Converted date feature to year for dimensionality reduction  
- Scaled features to improve model performance  
- Built and compared multiple regression models:  
  - **Linear Regression**  
  - **Support Vector Regression (SVR)**  
  - **Random Forest Regressor**  
- Evaluated models using R² Score, MAE, MSE, and RMSE  
- Visualized results through line plots, regression plots, and boxplots  
- Saved the best-performing model using **Joblib** for deployment

---

## 🛠️ Tools & Libraries
- **Programming:** Python  
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (LinearRegression, SVR, RandomForestRegressor)  
- **Model Persistence:** Joblib

---


---

## 📊 Workflow
1. **Data Preprocessing**
   - Convert `Date` to `Year`
   - Handle duplicates and missing values
2. **Feature Engineering**
   - Feature scaling using `StandardScaler`
3. **Model Training**
   - Train Linear Regression, SVR, and Random Forest models
4. **Evaluation**
   - Compare models using R², MAE, MSE, and RMSE
5. **Visualization**
   - Plot stock trends and model performance
6. **Deployment Ready**
   - Serialize best model using `joblib.dump()`

---

## 📌 Results
- **Random Forest Regressor** gave the highest accuracy and lowest error among the models tested.
- The model is ready to be deployed for predicting Tesla stock prices on unseen data.

---

## 🚀 Future Improvements
- Use more granular features (month, day, sentiment data, technical indicators)  
- Apply advanced time series models like LSTM or ARIMA  
- Deploy as a web app using Flask or Streamlit

---


