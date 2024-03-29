# Portfolio 

## Sales Forecasting Model - New Store Expansion 

Develop a comprehensive sales forecasting model utilizing various methods, including time series analysis, regression analysis, causal analysis, and machine learning. The model will undergo evaluation using industry-standard metrics (e.g., MAE, MAPE, RMSE) and its ability to dynamically update forecasts in response to new data from a holdout dataset.

The company aims to open 30 new stores annually in a new market and requires accurate daily sales forecasts for financial planning and ROI assessment. The challenge is predicting first-year sales for these new stores with a limited historical dataset.

**Analytical Problems to Address**

Identify trends and patterns in sales data.
Understand the relationship between sales and other factors.
Identify outliers and anomalies.
Proposed Solution:
Develop a comprehensive sales forecasting model utilizing various methods, including time series analysis, regression analysis, causal analysis, and machine learning. The model will undergo evaluation using industry-standard metrics (e.g., MAE, MAPE, RMSE) and its ability to dynamically update forecasts in response to new data from a holdout dataset.

**Expected Outcomes:**

The sales forecasting model will empower the company to:

Make informed decisions on staffing, inventory, and marketing for new stores.
Maximize profits and minimize losses.
Maintain high customer satisfaction through optimized operations.

**Key Features:**
Utilization of diverse forecasting methods.
Evaluation using industry-standard metrics.
Dynamic updating of forecasts in response to new data.

Enabling the company to strategically plan and optimize operations for new store expansions, ultimately enhancing financial outcomes and customer satisfaction.

### Analysis 

#### Exploratory Data Analysis (EDA): crucial step in the data analysis process for several reasons:
- Understand the Data: gain a preliminary understanding of the dataset. You can explore the structure, types, and formats of variables, ensuring clarity on what information is available.
- Detect Patterns and Trends: to identify patterns, trends, and relationships within the data. This is essential for uncovering insights that may guide subsequent analyses or hypotheses.
- Handle Missing Data:identify missing or incomplete information. Understanding the extent of missing data helps in deciding how to handle it, whether through imputation or exclusion.
- Identify Outliers and Anomalies: identifying outliers or anomalies that may skew your analysis. Detecting these data points is crucial for ensuring the robustness and accuracy of statistical models.
- Variable Distributions: understanding the distributions of variables is vital for choosing appropriate statistical tests and models. EDA allows you to check for normality, skewness, and kurtosis in the data.
- Feature Engineering:
- Validate Assumptions:
- Communication and Visualization:
- Formulate Hypotheses:

In summary, exploratory data analysis is a crucial preliminary step that lays the foundation for meaningful and accurate analyses. It helps researchers and data scientists understand the characteristics of the data, identify potential issues, and make informed decisions about how to proceed with further analyses.

<img src="https://github.com/dbhakti3450/predictive-model-bhakti-capstone/assets/134881202/4fdae15f-6e93-4f6c-a89c-843f08b667de"/>

![image](https://github.com/dbhakti3450/predictive-model-bhakti-capstone/assets/134881202/76c50bbf-3844-45d8-8ef0-9e856de59d9c)

For full EDA Notebook and Detail Explanation of Analytical Findings: 

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/dbhakti3450/bhaktidahal-capstone-github.io/blob/4afd7560e2be1821456dcad6783943edc8f4c3f7/Bhakti_Maverik_EDA_by_BonFire_Analytics.ipynb)

### Sales Forecasting - Model Building 

Modeling Notebook is found here: [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/dbhakti3450/bhaktidahal-capstone-github.io/blob/60989902cb246d95f9e892d400d7237cf0eb2f07/Sales_Forecasting_Maverik.ipynb)

Prophet model showed promising results for forecasting convenience store sales, especially with clustering and hyperparameter tuning. It outperformed other models like ARIMA and SARIMA that faced limitations in handling seasonality and holidays. Further optimization of Prophet model using more data and rolling origin is highly recommended for even better accuracy.

**Key Findings:**
ost sales data showed seasonal patterns, with summer peaks and winter troughs. Most sales data showed seasonal patterns, with summer peaks and winter troughs. We also noticed that some store features were contributing to the sales such as store offering pizza vs no pizza. Clustering improved forecasting accuracy for some models, especially the Prophet model. Clustering Model combined to the stores based on the features that were contributing to the sales. This hybrid model combines the output of clustering and the Prophet model.

In clustering analysis, data was organized into clusters, facilitating the identification of trends and patterns for each cluster's target variables.

In Cluster 1, the Prophet model's performance improved with hyperparameters, leading to more accurate predictions for Inside Sales and Food Sales. Unleaded Sales had moderate forecasting accuracy, while Diesel Sales saw a significant improvement with seasonality parameters.

Cluster 2 exhibited variations in the Prophet model's performance. Inside sales had more accurate forecasts without seasonality hyperparameters, while food service sales had moderate to high prediction errors. Unleaded sales improved with seasonality parameters, but diesel sales had a minor improvement.

Cluster 3 showed substantial forecast accuracy improvements for inside and food service sales with seasonality parameters.

Cluster 4 demonstrated more accurate forecasts for inside sales without hyperparameters, significant improvements for food service sales with hyperparameters, and notable enhancements for unleaded sales and minor improvements for diesel sales with hyperparameters.

**Unleaded - Cluster 4 Forecasting**
![image](https://github.com/dbhakti3450/bhaktidahal.github.io/assets/134881202/fbf0d14e-37e8-4ebe-a489-77458fdb64a3)
