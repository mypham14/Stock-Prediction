# Welcome to My Data Science Portfolio
Author: My Pham

Repository containing my portfolio of data science projects completed in iPython Notebooks and R Markdown files for educational and hobby purposes.

# Contents
### 1. Machine Learning
   - [Supervised Learning - Stock Price Prediction](https://github.com/mypham14/stock-price-prediction): a combination of regression models *(time series, regression machine learning, ensemble learning and deep learning)* to provide financial investors insights on a diversified portfolio of 6 companies representing 6 different industries and the S&P500 index and forecast stock prices of each company to investors make financial decisions based on the price movements
     - Extract stock prices of all companies over 20 years from Yahoo Finance and maintain a database of stock details in MySQL Server
     - Test a combination of models including ARIMA Time Series, Regression Machine Learning models (KNN, Linear Regression, Ridge, LASSO, Support Vector Machines (SVM - linear, poly, rbf)), Ensemble Learning (Bagging, Pasting, Adaboost and Gradient Boosting) and Deep Learning models (Long Short-Term Memory (LSTM)) to predict stock prices of the companies in the portfolio
     - Web scrape real-time stock prices of all companies
     - Create [Tableau dashboards](https://tabsoft.co/2DxdiBV) for all companies' stock prices for data analysis and visualization 
     - Automate the modeling process and deploy the chosen model into production in [Azure ML](https://bit.ly/3ksg24c) using R scripts
   - Supervised Learning - Heart Disease Prediction: a mix of classification models *(ensemble learning, classification machine learning, principal component analysis and deep learning)* to provide hospitals a filtering system that helps patients identify and prevent potential predictors of having a heart disease 
     - Perform data cleansing and exploratory data analysis
     - Apply a combination of models including Emsemble Learning (voting classifiers, bagging, pasting, adaboost and gradient boosting), Principal Component Analysis, Classification Machine Learning (KNN, Logistic Regression, Linear Support Vector Machine, Kernelilzed Support Vector Machine (rbf, poly, and linear), Decision Tree) and Deep Learning to predict whether a patient has a heart disease
     - Create Tableau dashboards for data analysis and visualization 
     - Automate the modeling process and deploy the chosen model into production in Azure ML

*Tools: pandas, numpy, matplotlib, seaborn, tensorflow, keras, beautifulsoup, requests, scikit-learn, statsmodels.tsa, mysql.connector*
