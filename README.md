# Advanced-Forecasting-Techniques-Project
Our project focuses on helping the retail businesses improve inventory planning to increase sales and reduce waste by forecasting future customer demand. We analyze the past demand patterns to predict for the upcoming weeks and months. We need to understand the seasonal trends, holiday effects, and consumer behavior over time so businesses can make smarter decisions. The questions we want to answer: when to increase for peak demand periods; how promotion or seasonal events influence demand; how far ahead accurate planning is possible. How external factors influence sales, such as the unemployment rate, fuel prices, and whether CPI corresponds with sales. The data contains these columns: Store: A unique identifier for each retail store.
Date: Represents the week of sales, indicating the specific weekly period for the recorded data.
Weekly_Sales: The total sales for the given store during that particular week.
Holiday_Flag: A binary indicator showing whether the week in question was a holiday week (1 for holiday, 0 for non-holiday).
Temperature: The recorded temperature on the day the sales data was collected.
Fuel_Price: The cost of fuel in the region corresponding to the store during the sales week.
CPI: Stands for Consumer Price Index, providing an economic indicator for the period.
Unemployment: The unemployment rate in the region during the sales week. 
We will implement three model categories: baseline models, classical time-series models, and advanced models. The models will be evaluated using a train-test split and multiple accuracy metrics. Results will be analyzed not only for accuracy but also for practical business insights. 
