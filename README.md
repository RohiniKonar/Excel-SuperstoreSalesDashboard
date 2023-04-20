# Excel-Superstore-Sales-Dashboard
Analysis of Superstore Sales and Profit Dashboard for 2014-2017

We use a superstore in our day to day life for buying anything and everything. Superstore business has to make important business decisions which are mostly based on the sales data. Here we are going to look at a superstore dataset which was picked from Kaggle and how few interesting insights were discovered.

If you are in data, I am sure you have heard about this dataset!
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

Changes made to the Dataset:
I have split the dataset into 3 tables namely - Superstore, Shipment and Category.

Steps:

1. Data extraction: I have downloaded the dataset from Kaggle and used excel for my analysis.
2. Data cleaning: removed unnecessary columns for my specific analysis, changed the data types, checked for duplicates, checked if there are rows with missing values.
3. Data transformation: I have used Power Query to load, tranform and analyse the dataset. Below are few transformation that I did with this data:
   - Loaded all the 3 tables into Power Query
   - Created the relationship by joining Superstore with Shipment and Category table. This was performed by using left join.
   - Cost measure was created in the Superstore table using sales and profit
4. Data Exploration/Analysis: performed data analysis by looking at the distribution of the data and correlations between variables to uncover insights. Performed the aggregation analysis with Pivot Tables and created appropriate visualizations.
5. Data Visualization: create a dashboard with the relevant visualizations and uncover meaningful insights to improve business performance.

Dashboard
![image](https://user-images.githubusercontent.com/32761695/233464755-503fa5ba-b55d-4750-97f3-71eb7537639f.png)

Data Analysis:

Insights
- Sales is highest in West region with $3,30,640 followed by East with $3,29,829.
- East region has the highest profit of $52,476. Whereas the lowest profit comes from Central with $11,408.
- Sales of Consumer product is highest among Corporate and Office products.
- California tops the list of highest sales followed by New York.
- Profit earned is highest in California which is followed by New York.
- Top 5 stated in terms of Sales and Profit are common i.e., Washington, Virginia, New York, Michigan and California.
- Profit was lowest in 2014 Qtr 3 which was $1,877 and the highest in 2016 Qtr 4 with $18,279.


Recommendations

- The superstore can check if there is any sales strategy that California is using because of which the sales and profit both are high when compared to others and the same can be applied in all states.
- In the central region even though the sales is high the profit is comparatively less so the superstore should focus on sales campaign and promotions.
