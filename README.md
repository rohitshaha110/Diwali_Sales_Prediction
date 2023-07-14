# **Diwali_Sales_Prediction**

Diwali is one of the most significant festivals in India, and businesses often experience a surge in sales during this period. Predicting sales accurately can help businesses optimize their inventory management, pricing strategies, and overall profitability.  The major challenge for a Retail store or eCommerce business is to choose product prices such that they get maximum profit at the end of the sales. Our project deals with determining product prices using machine-learning techniques based on historical retail store sales data. After generating the predictions, our model will help the retail store to decide the price of the products to earn more profits.

## Dataset
The dataset used for this project consists of historical sales data from previous Diwali festival. The data contained features like age, gender, marital status, categories of products purchased, city demographics, purchase amount etc. The data consists of 12 columns and 537577 records. Our model will be predicting the purchase amount of the products.

## Data Preparation
Used LabelEncoder for encoding the categorical columns like Age, Gender and City_Category
Used get_dummies from Pandas package for converting categorical variable State_In_Current_Years into dummy/indicator variables.
Filled the missing values in the Product_Category_2 and Product_Category_3

## Methodology
In this project, we employed a machine learning approach to predict sales during Diwali. The methodology involved data exploration, preprocessing, feature engineering, model selection, and evaluation of different models. We experimented with different algorithms, such as linear regression, Decision Tree Regression, Random Forest Regressor, and XGBoost Regressor, to find the best-performing model.

## Evaluation Metric
Root Mean Square Error (RMSE) is a standard way to measure the error of a model in predicting quantitative data. It’s the square root of the average of squared differences between prediction and actual observation.

## Conclusion
Implanted multiple supervised models such as Linear Regressor, Decision Tree Regressor, Random Forest Regressor and XGBoost Regressor. Out of these supervised models, based on the RMSE scores XGBRegressor/XGBoost Regressor was the best performer with a score of 2875.55.
