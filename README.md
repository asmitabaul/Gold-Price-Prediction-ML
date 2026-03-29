-Overview:
This project builds a regression-based machine learning pipeline to predict gold prices using key macroeconomic indicators such as USD-INR exchange rate, Brent crude oil prices, CPI inflation, and repo rate.

The focus is on analyzing how different models perform on real-world financial data and how economic variables influence price movement.

-Features:
USD-INR Exchange Rate
Brent Crude Oil Prices
CPI Inflation (%)
Repo Rate (%)

-Exploratory Analysis:
Time-series visualization of gold price trends
Scatter plots to examine relationships with macro variables
Correlation heatmap for feature interaction analysis

-Models Used:
Linear Regression- Baseline
Ridge Regression- Regularised Linear
Random Forest- Ensemble
XGboost- Boosting


-Evaluation Metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score


Time-based train-test split (80:20) was used to avoid data leakage.

-Results
Model	               MAE	    RMSE	   R²
Linear Regression	   
Ridge Regression	
Random Forest	
XGBoost	

-Tech Stack:
~Python
~Pandas, NumPy
~Scikit-learn
~XGBoost
~Matplotlib, Seaborn

-Project Structure
gold-price-prediction/      

├── data/             
├── notebooks/        
├── outputs/           
├── README.md

