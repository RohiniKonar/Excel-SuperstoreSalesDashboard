# Excel-Superstore-Sales-Dashboard
Analysis of Superstore Sales and Profit Dashboard for 2014-2017

We use a superstore in our day to day life for buying anything and everything. Superstore business has to make important business decisions which are mostly based on the sales data. Here we are going to look at a superstore dataset which was picked from Kaggle and how few interesting insights were discovered.

If you are in data, I am sure you have heard about this dataset!
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

Steps:

1. Data extraction: I have downloaded the dataset from Kaggle and used excel for my analysis.
2. Data cleaning: removed unnecessary columns for my specific analysis, changed the data types, checked for duplicates, checked if there are rows with missing values.
3. Data transformation: I have used Power Query to load, tranform and analyse the dataset. Below are few transformation that I did with this data:
   - Loaded all the 3 tables into Power Query
   - Created the relationship by joining Superstore with Shipment and Category table. This was performed by usinh left join.
   - Cost measure was created in the Superstore table using sales and profit
   - Profit percentage was created in the Superstore table
4. Data Exploration/Analysis: performed data analysis by looking at the distribution of the data and correlations between variables to uncover insights. Performed the aggregation analysis with Pivot Tables and created appropriate visualizations.
5. Data Visualization: create a dashboard with the relevant visualizations and uncover meaningful insights to improve business performance.

Dashboard

Data Analysis:
Insights
•	Sales is highest in West region with $3,30,640K followed by East with $3,29,829K.
•	East region has the highest profit of $52,476K. Whereas the lowest profit comes from Central with $11,408K.
•	Sales of Consumer product is highest among Corporate and Office products.
•	California tops the list of highest sales followed by New York.
•	Almost a 1/3 of the bookings were cancelled and almost 70% of those cancellations came from customers who made their bookings online.
•	The average duration of stay remains quite constant throughout the year, with the average being 3.1 days.
•	Bookings are made much more in advance for the months June-October.

Recommendations

•	The superstore can check if there is any sales strategy that California is using because of which the sales and profit both are high when compared to others and the same can be applied in all states.
•	In the central region even though the sales is high the profit is comparatively less so the superstore should focus on sales campaign and promotions.
