# Electric Vehicle Sales Analysis and Prediction in India

This project explores trends in Electric Vehicle (EV) sales across Indian states and predicts sales quantity using machine learning techniques. The goal is to provide insights into the growth of the EV market and develop a regression model to forecast future sales.

---

## Project Objectives

- Clean and preprocess EV sales data for consistency and accuracy.
- Perform Exploratory Data Analysis (EDA) to uncover patterns by year, month, state, vehicle type, and category.
- Engineer features to support effective modeling.
- Train a Random Forest regression model to predict EV sales quantity.
- Evaluate model performance using RMSE and feature importance.

---

## Tools and Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (RandomForestRegressor, train_test_split, evaluation metrics)
- Jupyter Notebook or Google Colab

---

## Dataset

- Source: Electric Vehicle Sales by State in India (CSV format)
- Features include:
  - Date
  - Year
  - Month_Name
  - State
  - Vehicle_Class
  - Vehicle_Category
  - Vehicle_Type
  - EV_Sales_Quantity

---

## Project Workflow

### 1. Data Preprocessing

- Converted data types (`Year` to integer, `Date` to datetime)
- Converted categorical columns to category types
- Filled missing values:
  - Numeric columns: median
  - Categorical columns: mode
- Removed duplicate records

### 2. Exploratory Data Analysis (EDA)

- Year-wise and month-wise sales trends
- State-wise EV sales comparison
- Distribution by vehicle category and vehicle type
- Visualized using bar plots and line charts

### 3. Feature Engineering

- Extracted `Month` and `Day` from `Date`
- Applied one-hot encoding to categorical variables
- Removed unnecessary columns like `Date`, `Month_Name`

### 4. Model Training and Evaluation

- Model: Random Forest Regressor
- Features: Engineered numeric and encoded categorical data
- Target: EV_Sales_Quantity
- Metrics: Root Mean Squared Error (RMSE), Feature Importance
- Visuals:
  - Actual vs. Predicted scatter plot
  - Top 10 important features bar chart

---

## Results and Insights

- Strong yearly growth trend in EV sales across multiple states
- Certain states showed dominant contributions to overall sales
- Vehicle type and category significantly impacted sales quantity
- Random Forest model provided good predictive performance based on RMSE
- Feature importance analysis highlighted which attributes drive EV sales the most

---

## Future Improvements

- Incorporate external data (e.g., fuel prices, policy changes, subsidies)
- Use time series forecasting models like ARIMA, Prophet, or LSTM
- Build dashboards for real-time trend monitoring and forecasting
- Apply clustering to segment EV markets by region or vehicle class
- Evaluate other regression models and perform hyperparameter tuning

---

## Author

**TARUN C**  

