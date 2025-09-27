### Supply Chain - Customer targeted Sales and Fraud Detection Analysis

By Jennie Juvvanapudi

#### Executive summary:
This project focuses on building a Customer Sales Classification Model to improve customer segmentation and drive business growth. By leveraging transactional and customer-level data from a supply chain dataset, the project identifies distinct customer segments and develops predictive models to classify customer sales behavior. The outcomes will support strategic decision-making by enabling the company to better understand customer needs, enhance targeting strategies, improve responsiveness, and increase overall revenue.

#### Rationale
Why should anyone care about this question?

Understanding customer behavior is critical for businesses in a competitive marketplace. Organizations often face challenges in tailoring marketing campaigns, offering personalized experiences, and optimizing sales strategies. A customer sales classification framework helps in addressing these challenges by:
* Identifying high-value customers by sales and region.
* Predicting customer purchase patterns.
* Enhancing customer engagement through targeted campaigns.
* Improving resource allocation across sales and marketing.
By solving this problem, the company can strengthen customer relationships and maximize revenue opportunities.


#### Research Question
The central research question for this project is:
 How can we classify customers based on their sales and transaction patterns to optimize targeting strategies and improve responsiveness and revenue? 
Supporting sub-questions:
* Which customer attributes most strongly influence sales behavior?
* What are the most effective machine learning models for classifying customer sales patterns?
* How do different feature engineering and preprocessing techniques affect classification performance?

 I will be using Classification type ML models and Regression type ML models against the Neural Network models with the same dataset. This project aims to compare 9 popular machine learning classifiers and 7 regressors type machine learning models and measure their performance against neural network models to find out which machine learning model performs better. 

This project aims to compare 9 popular machine learning classifiers and 7 regressors type machine learning models and measure their performance against neural network models to find out which machine learning model performs better. Since the dataset used is related to supply chain important parameters are identified and the machine learning models are trained with the dataset for detection of fraud transactions, late delivery of orders, sales revenue and quantity of products which customer orders.

#### Data Sources
What data will you use to answer you question?

The analysis uses the DataCo Supply Chain dataset, which includes detailed records of customer demographics, transactions, product sales, and supply chain operations. Specifically:
* Customer Data: Demographic and segmentation details.
* Transaction Data: Sales amounts, order quantities, and dates.
* Product Data: Product categories, pricing, and supply chain attributes.
* Supply Chain Data: Order processing, delivery, and fulfillment details.
This dataset provides a holistic view of customer interactions, enabling robust classification modeling.
DataCo SMART SUPPLY CHAIN FOR BIG DATA ANALYSIS - Mendeley Data


#### Methodology
What methods are you using to answer the question?

Methodology
The project follows a structured machine learning and statistical modeling pipeline:
1. Data Preprocessing & Quality Checks
o Handle missing values, duplicates, outliers, and incorrect data types.
o Feature encoding (One-hot, Label, Target encoding).
o Scaling (StandardScaler, MinMaxScaler).
2. Exploratory Data Analysis (EDA)
o Univariate, bivariate, and multivariate analysis to uncover trends.
o Visualization of customer segments, purchase frequencies, and correlations.
3. Feature Engineering & Selection
o Creation of derived variables (e.g., purchase frequency, average order value).
o Dimensionality reduction using PCA.
o Recursive Feature Elimination (RFE) and correlation-based filtering.
4. Model Development   Classification Models
o Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, and K-Nearest Neighbors (KNN).
o Hyperparameter tuning using GridSearchCV.
5. Model Development   Time Series Forecasting
o ARIMA (Auto-Regressive Integrated Moving Average) modeling for analyzing sales demand trends over time.
o Seasonal and trend decomposition of time series to capture cyclical purchasing patterns.
o Forecasting future customer demand and integrating results into classification insights.
6. Model Evaluation
o Metrics: Precision, Recall, F1-Score, and ROC-AUC for classification models.
o AIC/BIC, RMSE, and forecast accuracy for ARIMA models.
o Comparison of classification and forecasting models to determine the best-performing combination.
7. Business Implications
o Evaluation of misclassification (false positives/false negatives) in terms of customer targeting costs and revenue impact.
o Use of ARIMA forecasts for proactive inventory management, marketing campaigns, and customer engagement strategies.

#### Results
What did your research find?

#### Next steps
What suggestions do you have for next steps?

#### Outline of project


Modeling Approach

The project compares multiple machine learning and statistical models to identify the best-performing techniques:

Classification Models (Fraud Detection, Late Delivery Prediction):
Logistic Regression, Linear Discriminant Analysis, Gaussian Naive Bayes, Support Vector Machines, k-Nearest Neighbors, Random Forest, Extra Trees, Extreme Gradient Boosting, and Decision Trees.

Evaluation Metrics: Accuracy, Recall, F1-Score.

Regression Models (Sales & Quantity Prediction):
Linear Regression, Ridge, Lasso, Decision Tree Regression, Random Forest Regression, Extreme Gradient Boosting Regression, and LightGBM Regression.

Evaluation Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE).

Neural Networks:
Benchmarked against classifiers and regressors to evaluate performance improvements.

Time Series Forecasting (Sales/Demand Trends):
ARIMA (Auto-Regressive Integrated Moving Average) is applied to sales and order quantities to capture seasonal patterns and forecast future demand trends.

Evaluation Metrics: AIC/BIC, RMSE, Forecast Accuracy.

This project aims to compare the above popular machine learning classifiers and regressors type machine learning models and measure their performance against neural network models to find out which machine learning model performs better


##### Contact and Further Information
