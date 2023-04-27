In this project, I analyze Walmart's weekly sales data across 45 different stores to gain insights into their sales performance and identify trends and patterns. I then use this data to forecast future sales, which can assist Walmart in making strategic decisions.
The dataset was obtained from Kaggle website. It consists of Walmart's weekly sales from 2010-02-05 to 2012-11-01. The file has the following columns:

Store: the store number
Date: the week of sales
Weekly_Sales: sales for the given store
Holiday_Flag: whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
Temperature: Temperature on the day of sale
Fuel_Price: Cost of fuel in the region
CPI: Prevailing consumer price index
Unemployment: Prevailing unemployment rate in percentage

According to my analysis, sales exhibit a notable disparity between holiday and non-holiday weeks, with an average doubling in sales during holiday periods. Furthermore, there is a clear seasonal pattern in the sales data. The most successful stores experience sales that are up to 500% higher compared to the least successful ones.

The Random Forest Regressor model has demonstrated excellent performance in predicting future sales, yielding an RMSE (Root Mean Square Error) of 1.45e+05. This level of accuracy is significant, as it aligns closely with the median sale value, with an 85% proximity.
