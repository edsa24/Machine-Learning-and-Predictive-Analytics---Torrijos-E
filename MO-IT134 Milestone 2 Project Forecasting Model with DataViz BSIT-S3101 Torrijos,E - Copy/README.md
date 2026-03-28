6-Month Sales Forecasting Model

📌 Project Overview



This project aims to forecast future monthly sales using a Linear Regression model. The objective is to help businesses make informed decisions in inventory planning, pricing strategies, and revenue management by predicting sales trends for the next 6 months.



The project uses historical transaction data to identify patterns and generate future sales predictions.



🎯 Objectives

Analyze historical sales transaction data

Perform data cleaning and preprocessing

Select relevant features for modeling

Build a predictive model using Linear Regression

Forecast sales for the next 6 months

Visualize and interpret forecasted results

📂 Dataset

File: Initial\_Project\_Forecasting\_Model.xls

Records: 5,342 rows

Features: 27 columns

🔑 Key Variables:

MonthlySales → Target variable

Quantity → Number of items sold

Product\_Price\_x → Product price

Company\_Profit → Profit generated

Rolling3MonthSales → Recent sales trend

Month, Week, IsWeekend → Time-based features

⚙️ Data Preprocessing



The following preprocessing steps were performed:



Checked for missing values in the dataset

Identified missing data in columns such as:

Company\_Name

Product\_Name

Product\_Price\_y

Filled missing values in numeric columns using the median:

Quantity

Product\_Price\_x

Company\_Profit

Rolling3MonthSales

Selected relevant features for prediction



These steps ensured that the dataset was clean and suitable for modeling.



🧠 Feature Selection



The following features were used to train the model:



Time Features: Month, Week, IsWeekend

Sales Features: Quantity, Product\_Price\_x

Business Feature: Company\_Profit

Trend Feature: Rolling3MonthSales



These features were selected because they capture both historical behavior and recent sales trends.



🤖 Model Used

Linear Regression

A simple and interpretable machine learning algorithm

Suitable for predicting continuous values such as sales

Establishes relationships between input features and the target variable

🔮 Forecasting Approach



To generate future predictions:



A dataset representing the next 6 months was created

Average values were used for key variables:

Quantity

Product Price

Company Profit

Rolling3MonthSales

The trained Linear Regression model was used to predict future sales

📊 Forecast Results

📌 6-Month Forecast Table

Month	Predicted Sales	Change %

Month 1	-1.62	0%

Month 2	-1.68	-3.3%

Month 3	-1.73	-3.2%

Month 4	-1.24	+28.5%

Month 5	-1.29	+4.3%

Month 6	-1.34	+3.9%

📈 Visualizations



The project includes the following visual outputs:



📊 Forecasted Sales Bar Chart

📉 Historical vs Forecasted Sales Line Graph



These visualizations help in understanding trends and comparing past and predicted sales performance.



🔍 Insights \& Interpretation

Sales show a declining trend in the first 3 months

A recovery begins from Month 4 onward

Historical data shows high volatility, while forecasted values are more stable

The model captures general trends but may not reflect extreme fluctuations

💡 Business Implications:

Helps in inventory planning

Supports budget forecasting

Assists in marketing and sales strategy decisions

⚠️ Limitations

Forecasting uses average values for future inputs

Does not account for seasonality or external factors

Linear Regression may not capture sudden spikes or drops

🚀 Future Improvements

Apply advanced models:

Random Forest

ARIMA (time-series forecasting)

Incorporate seasonal patterns

Include external data such as promotions or market trends

Improve feature engineering

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

📁 Project Structure

├── Initial\_Project\_Forecasting\_Model.xls

├── Milestone 2 Project Forecasting Model with DataViz.ipynb

├── Milestone2\_6Month\_Forecast.xls

├── Milestone2\_Featured\_Data.xls

├── README.md

