# Covid-case-Prediction

What happens when data science meets a global health crisis?
In this project, I explored various time series and machine learning techniques to forecast daily global COVID-19 death counts, comparing their performance to identify the most accurate and robust model.

### Goal
To predict global COVID-19 daily deaths using real-world data and evaluate how different models perform under the same forecasting task. The goal was to simulate real-life decision-making support for healthcare and policy teams during a pandemic.

### Models & Techniques Used
Method	                Type	                                                             Highlights
SARIMAX	              Statistical	                                          Seasonality, autoregression, exogenous variables
Prophet	              Decomposable model	                                  Handles trend shifts, missing data, and holidays
XGBoost               Regressor	Machine Learning	                          Captures nonlinear patterns with engineered features
FFNN (Keras)	        Deep Learning	                                        Learns complex temporal dependencies



## Key Takeaways
Time series forecasting is not one-size-fits-all — data quality and patterns dictate model success.
SARIMAX and Prophet offer strong baselines, especially when interpretability matters.
ML and deep learning models require careful feature engineering and more tuning but can shine with richer datasets.
