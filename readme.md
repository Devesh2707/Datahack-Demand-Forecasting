# Janatahack: Demand Forecasting
***
### Problem Statement
One of the largest retail chains in the world wants to use their vast data source to build an efficient forecasting model to predict the sales for each SKU in its portfolio at its 76 different stores using historical sales data for the past 3 years on a week-on-week basis. Sales and promotional information is also available for each week - product and store wise. 

However, no other information regarding stores and products are available.
Forecast accurately the sales values for every such product/SKU-store combination for the next 12 weeks accurately.

### Data Description
| **Variable**    | **Defination**                                                |
|-----------------|---------------------------------------------------------------|
| record_id       | Unique ID for each week store sku combination                 |
| week            | Starting date of the week                                     |
| store_id        | Unique ID for each store                                      |
| sku_id          | Unique ID for each product                                    |
| total_price     | Sales Price of the product                                    |
| base_price      | Base Price of the product                                     |
| is_featured_sku | Was part of the featured item of the week                     |
| is_display_sku  | Product was on display at a prominent place at the store      |
| units_sold      | (Target) Total Units sold for that week-store-sku combination |

### Evaluation Metric
The evaluation metric for this competition is 100*RMSLE (Root Mean Squared Log Error).

### Result
#### No. of Registered: 13410
#### Public Leaderboard Rank: 93
#### Private Leaderboard Ranl: 109

[Leaderboard](https://datahack.analyticsvidhya.com/contest/janatahack-demand-forecasting/#LeaderBoard)
