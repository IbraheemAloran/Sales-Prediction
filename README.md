# 📈 Time Series Sales Forecasting & Exploratory Data Analysis

A comprehensive **time series analysis and forecasting project** that explores historical sales data to uncover trends, seasonality, and patterns, and predicts future sales using multiple machine learning and deep learning approaches.

This project combines **Exploratory Data Analysis (EDA), feature engineering, and advanced forecasting models** including **XGBoost, LSTM, and Chronos (LLM-based Transformer model)** to build accurate predictive models.

The final system achieved **~89% forecasting accuracy for monthly sales predictions**.


<img width="1280" height="721" alt="image" src="https://github.com/user-attachments/assets/08c1ee59-9746-4978-90f7-55f65416f5a8" />



---

# 🚀 Project Overview

Understanding future sales trends is essential for business planning, inventory management, and revenue forecasting. This project performs a full **end-to-end time series analysis pipeline**, including:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualizations and Dashbaords with Power BI
- Time series decomposition
- Feature engineering with lag and temporal features
- Training multiple forecasting models
- Performance evaluation and comparison

The goal was to identify **patterns and seasonality in sales data** and develop models capable of generating reliable forecasts.

---
# 🔎 Exploratory Data Analysis (EDA)

Extensive exploratory analysis was conducted to understand the characteristics of the dataset.

### Key Analysis Performed

- Time series visualization
- Distribution analysis
- Trend identification
- Seasonal pattern detection
- Outlier detection
- Correlation analysis

### Visualizations Created

Examples of visualizations generated during analysis:

- Sales trends over time
- Rolling mean and variance
- Monthly seasonal patterns
- Lag correlation plots
- Autocorrelation (ACF)
- Partial autocorrelation (PACF)

These visualizations helped identify:

- Long-term growth trends
- Seasonal sales fluctuations
- Temporal dependencies between observations

---

# ⚙️ Feature Engineering

Time series forecasting models rely heavily on engineered temporal features.

### Lag Features

Lag features allow models to learn dependencies between past and future observations.

### Date-Time Features

Temporal features extracted from timestamps:

- Month
- Year
- Quarter
- Day of week (if applicable)
- Seasonal indicators

These features help models learn **seasonality patterns**.

---

<img width="1284" height="725" alt="image" src="https://github.com/user-attachments/assets/2e104480-fb21-4a5b-b269-1a19a22176cf" />

<img width="1276" height="716" alt="image" src="https://github.com/user-attachments/assets/93b322e4-5498-41bc-847d-c467e5e67312" />


# 🧠 Forecasting Models

Multiple machine learning and deep learning models were implemented to compare performance.

---

# 1️⃣ XGBoost Model

**XGBoost** is a gradient boosting algorithm that performs well on structured/tabular datasets.

### Advantages

- Handles non-linear relationships
- Robust to missing data
- Efficient training
- Strong performance on tabular datasets

# 2️⃣ LSTM Model (Deep Learning)

A **Long Short-Term Memory (LSTM)** neural network was implemented to capture sequential dependencies in time series data.

LSTMs are well suited for modeling **long-range temporal relationships**.


# 3️⃣ Chronos (Transformer-based Forecasting)

The project also leveraged **Chronos**, a **large language model–based time series forecasting framework** built on transformer architectures.

Chronos treats time series forecasting as a **sequence modeling problem**, similar to language modeling.

### Advantages

- Captures long-range dependencies
- Handles irregular patterns
- Scales well with large datasets


# 📈 Model Evaluation

Models were evaluated using standard forecasting metrics.

### Metrics Used

| Metric | Description |
|------|------|
| MAE | Mean Absolute Error |
| RMSE | Root Mean Squared Error |
| MAPE | Mean Absolute Percentage Error |
| Forecast Accuracy | Overall prediction performance |

---

### Final Result

| Model | Forecast Accuracy |
|------|------|
| XGBoost | High performance on tabular features |
| LSTM | Captures sequential patterns |
| Chronos | Strong contextual modeling |
| **Best Model Performance** | **~89% monthly forecasting accuracy** |

The ensemble of approaches demonstrated that both **traditional ML and deep learning models** can effectively model sales trends.
