# Inventory-Forecasting
This project aims to support an online gift store with inventory planning by forecasting inventory levels for each product using Multi Linear Regression and Random Forest. The CRISP-DM method was used to guide the data mining phases, including business understanding, data understanding, data preparation, modeling, and evaluation. 

Additionally, in this analysis, we answered the following key questions to better understand factors that influence inventory levels:
1. What products, on average, are ordered in large volumes?
2. What products are in high demand based on sales volume and frequency of transactions?
3. Are there any seasonal factors that influence customer behavior?
4. What products are in high demand based on sales volume and frequency of transactions?
Link to the dashboard: https://public.tableau.com/app/profile/mariiamohyla/viz/HowOnlineRetailcanimproveitsinventoryplanning/InsightsintoOnlineGiftStoreDemand

To sum up, Random Forest performed better compared to the Multi Linear regression by yielding lower MSE, RMSE, and MAPE evaluation metrics. Random Forest provides moderately accurate predictions, suggesting that the model generally offers improvement over simpler models like Multi Linear Regression. The MAPE of 19.33% suggests that the forecasts would deviate by around one-fifth of the actual values. Based on the RMSE value the prediction error is on average 2-3 units of product per month. 
<img width="669" alt="Screenshot 2024-05-24 at 6 39 09 PM" src="https://github.com/mariia-8/Inventory-Forecasting/assets/111792836/64c3bce8-b205-4010-870d-f5964eb7cb9b">

However, there is still a risk associated with using the Random Forest Model. The predicted results underestimated the quantity by 13.7%, leading to a 14.8% difference in revenue.
<img width="915" alt="Screenshot 2024-05-24 at 6 39 42 PM" src="https://github.com/mariia-8/Inventory-Forecasting/assets/111792836/870dd34a-2bd0-433a-9563-1c9ceb9eae84">
