# Customer Lifetime Value Prediction
This project involves predicting customer lifetime value (CLV) over a 3-month period using a real-world retail transaction dataset.# Customer-Lifetime-Value-Analysis

### Data
The dataset [Link for Dataset]([url](https://www.kaggle.com/datasets/carrie1/ecommerce-data/)) contains 500K transaction records for a UK online retailer between Dec 2010 - Dec 2011. It has 8 features like invoice number, product details, price, customer ID, etc.

### Analysis Steps
The key steps are:

* Data loading and inspection
* Preprocessing - remove cancelled orders, filter timeframe, add sales column
* Aggregate by customer ID and time period to get order summary stats
* Visualize purchase frequency distribution for repeat customers
* Engineer 3-month CLV target and feature set for modeling
* Train/test split
* Fit linear regression model to predict 3-month CLV
* Evaluate model performance with RMSE, MAE, etc

### Model Performance
The linear regression model achieves:

* RMSE of $1,880 on test set
* MAE of $449 on test set
