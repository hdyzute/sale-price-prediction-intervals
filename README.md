# sale-price-prediction-intervals
"House sale price prediction with Gradient Boosting and prediction intervals."

# House Sale Price Prediction with Gradient Boosting

This project demonstrates how to predict house sale prices using **Gradient Boosting Regressors** with quantile regression to estimate **prediction intervals**.  
It includes preprocessing pipelines, model training, evaluation metrics (RMSE, Winkler Score, Coverage), and visualization of prediction intervals.

---

## 📌 Features
- Data preprocessing with **scikit-learn Pipelines & ColumnTransformer**
- Handling:
  - Missing values (numeric + categorical)
  - Categorical encoding with **OrdinalEncoder**
  - Date feature extraction (year, month, week, day of week)
- Model training:
  - **GradientBoostingRegressor** with:
    - Median prediction (`loss="squared_error"`)
    - Lower quantile (5%)
    - Upper quantile (95%)
- Evaluation:
  - **RMSE** for median predictions
  - **Winkler Score** and **Coverage** for prediction intervals
- Visualization of prediction intervals vs. actual values

---

## 📂 Project Structure

