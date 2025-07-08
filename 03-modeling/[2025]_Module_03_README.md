Module 3: Time Series Modeling & Forecasting
This module focuses on applying time series forecasting techniques to financial stock market data. It builds on the cleaned and engineered dataset from Module 2.

🔧 Topics Covered
✅ ARIMA Modeling (AutoRegressive Integrated Moving Average)

✅ Walk-forward validation strategy

✅ Target variable: is_positive_growth_30d_future

✅ Manual rule-based prediction strategies (pred0 to pred5)

✅ Decision Tree Classifier tuning (max_depth sweep from 1 to 20)

✅ Precision evaluation on TRAIN, VALIDATION, and TEST splits

✅ Handling macroeconomic indicators (e.g., FEDFUNDS, DGS10, Brent Oil)

✅ Feature Engineering with dummy variables for Month & Week

📁 Key Files
[2025]_Module_3_Colab_Time_Series_Modeling.ipynb — main notebook for experimentation

stocks_df_combined_2025_06_13.parquet.brotli — dataset containing prices, indicators, and engineered features

test_pmdarima.py — script for testing ARIMA implementation

requirements.txt — optional environment specification (if used)

🚀 Output
Trained and tuned models (ARIMA, DecisionTreeClassifier)

Precision scores for multiple rule-based and ML models

Insight into seasonal patterns and macro trends

Prediction columns: pred0 through pred6_clf_best

