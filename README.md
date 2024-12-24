# Online-Retail-EDA

## Summary ##
By conducting EDA, identifying patterns and outliers, and creating visualizations, allowed me to uncover key trends and make data-driven decisions and recommendations to optimize the online retail store's operations.

## Approach ##
1. Load and perform data cleaning by handling missing values, removing any redundant or unnecessary columns, and identifying outliers.
2. Perform data visualization to gain insights into the dataset by generating histograms.
3. Analyze the sales trends over time. Identify the busiest months and days of the week in terms of sales.
4. Explore the top-selling products and countries based on the quantity sold.
5. Draw conclusions and summarize the findings from the EDA.

## Conclusion ##
#### Duplicate rows ####
There were even 71.183 duplicated rows, or approx. 13% of all data. This is a significant percentage, so I propose their replacement with new unique data. 

#### Outliers ####
In the 'Quantity' column there were 52.547 outliers, which is approx. 11% of all data.
In the 'UnitPrice' column there were 28.570 outliers, or approx. 6% of all data.
I dropped the outliers from both 'Quantity' and 'UnitPrice' columns, but maybe the outliers from 'Quantity' column should be replaced with mean values because of the big percentage.


#### Insights ####
Top-selling product by quantity was JUMBO BAG RED RETROSPOT followed by WHITE HANGING HEART T-LIGHT HOLDER and LUNCH BAG RED RETROSPOT.
I propose to continue sucessful marketing campaigns on these three products, while for the rest products the company should allocate resources to promote those products better.
The busiest month in terms of sales is November, followed by December and October. It is expected, because during November there are several traditional campaigns ("Black Friday" etc.), and in December customers buy presents for Christmas and New Year.
Special attention and promotions should be applied in April and February, as the least busiest months in terms of sales.
The busiest weekdays are Tuesdays and Thursdays, with further focus on Fridays and Sundays as the least busiest weekdays. The dataset doesn't have records for sales in Saturdays, so this day is excluded from the analysis. Taking into account that the store is open 24/7/365, it should utilize the advantage of selling especially on Sundays, because the other retail stores are mostly closed.
