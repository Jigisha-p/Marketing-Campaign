# Marketing Campaigns

### Problem Scenario:
‘Marketing mix’ is a popular concept used in implementing marketing strategies. A marketing mix includes multiple areas of focus as part of a comprehensive marketing plan. This all revolves around the four Ps of marketing - product, price, place, and promotion.

### Problem Objective:
Perform exploratory data analysis and hypothesis testing to gain a better understanding of the various factors that contribute to customer acquisition.

### Steps:
- Import data and investigate variables like Dt_Customer and Income, etc.
- Income values for a few customers are missing.<br>
Perform missing value imputation.<br>
Assume that the customers with similar education and marital status make the same yearly income, on average.<br>
clean the data before performing this. For data cleaning, look into the categories of education and marital status. <br>
- Create variables to populate the total number of children, age, and total spending.<br>
(From the number of purchases through the three channels, people can derive the total purchases.)
- Create box plots and histograms to understand the distributions and outliers. Perform outlier treatment.
- Use ordinal encoding and one hot encoding according to different types of categorical variables.
- Create a heatmap to showcase the correlation between different pairs of variables.<br><br>
- Test the following hypotheses:

1. Older people are not as tech-savvy and probably prefer shopping in-store.
2. Customers with kids probably have less time to visit a store and would prefer to shop online.
3. Other distribution channels may cannibalize sales at the store.
4. Does the US fare significantly better than the rest of the world in terms of total purchases?<br>


- Use appropriate visualization to help analyze the following:

1. Which products are performing the best, and which are performing the least in terms of revenue?
2. Is there any pattern between the age of customers and the last campaign acceptance rate?
3. Which Country has the greatest number of customers who accepted the last campaign?
4. Do you see any pattern in the no. of children at home and total spend?
5. Education background of the customers who complained in the last 2 years.
