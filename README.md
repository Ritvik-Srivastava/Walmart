
# Walmart Data Analysis

A brief description of what this project does and who it's for

Walmart Sales Data Analysis
About
This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of of different products, customer behaviour. The aims is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition.

"In this recruiting competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact." source

Purposes Of The Project
The major aim of thie project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.

About Data
The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:

Column	
Description	Data Type


![snap13](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/a6bcab64-76d8-4c6d-917f-045495032b8b)

Analysis List

1.Product Analysis

Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

2.Sales Analysis

This analysis aims to answer the question of the sales trends of product. The result of this can help use measure the effectiveness of each sales strategy the business applies and what modificatoins are needed to gain more sales.

3.Customer Analysis

This analysis aims to uncover the different customers segments, purchase trends and the profitability of each customer segment.

Approach Used
Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.

1.Build a database
2.Create table and insert the data.
3.Select columns with null values in them. 
There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.

![Screenshot 2024-01-22 124352](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/c896f4b1-2e75-4cc2-bc32-3ce1698d17bd)


Feature Engineering: This will help use generate some new columns from existing ones.

![snap1](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/5c9600f4-4211-4e61-8ea5-e4d27b5d5703)

Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.

Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.

Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

Conclusion:

Business Questions To Answer

Generic Question

How many unique cities does the data have?




In which city is each branch?



![Screenshot 2024-01-22 124816](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/4396eecd-8702-4862-bc93-278002968a1f)



Product

How many unique product lines does the data have?

![snap3](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/d83c5250-4c65-45b2-87cb-98291085b9aa)



![snap4](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/1b48513c-ee17-4b7a-885c-12959fc03938)

What is the most common payment method?

![snap2](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/a328076b-ddef-4184-bb26-28b814c17029)

What is the most selling product line?

![snap3](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/689302b4-f4c7-4518-878a-087ddca47054)
What is the total revenue by month?
![snap4](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/d93ece3f-5d1b-4c43-b751-45e45dcfa5b8)
What month had the largest COGS?
![snap5](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/061c2d27-4089-41ee-be7a-eb77722421ef)
What product line had the largest revenue?
![snap6](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/4512dffa-c780-4104-82fd-dcca666f4f71)
What is the city with the largest revenue?

![snap4](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/b726560f-863c-49af-bd20-9b84dda6a547)
What product line had the largest VAT?

![snap5](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/131b98a4-764a-4492-9f4f-b5fe0208a0cb)

Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
Which branch sold more products than average product sold?

![snap6](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/f94335c7-7218-4409-b64d-a1adc0c4bce9)

What is the most common product line by gender?

![snap7](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/5342231c-1f99-415f-b69f-3f30c60b9674)
What is the average rating of each product line?

![snap8](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/9c01bdf0-9c6a-453b-b906-96d7b3223077)


Sales

Number of sales made in each time of the day per weekday

![snap2](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/cc49b3ab-b68e-4f25-9eaf-072e006c2220)

Which of the customer types brings the most revenue?

![snap3](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/fbf0c259-1a97-42e2-83a1-bb6063970a91)

Which city has the largest tax percent/ VAT (Value Added Tax)?

![snap4](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/d28b31e0-4645-425d-81f3-0a26271ba06a)

Which customer type pays the most in VAT?

![snap5](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/843e3661-f305-4477-8668-7fe9de95c861)

Customer

How many unique customer types does the data have?

![snap4](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/9f874058-d06b-4fe4-b6c5-f9699c7d2729)

How many unique payment methods does the data have?

![snap5](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/5fdafdf9-8d5f-429c-9803-2349b443e816)





Which customer type buys the most?

![snap6](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/4296848e-903e-4146-aab2-b9389e276757)

What is the gender of most of the customers?

![snap7](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/918d59a5-89d7-4b10-9a1b-b0e26e3d9a7c)

What is the gender distribution per branch?

![snap8](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/59ff00af-3dcc-4c7c-8eaa-01cdb3285ad5)

Which time of the day do customers give most ratings?

![snap9](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/229d57e1-a257-4ad4-8752-dc79d6d1a591)

Which time of the day do customers give most ratings per branch?

![snap10](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/972260f8-f7a1-4d30-a3d8-09c9bf283c06)

Which day fo the week has the best avg ratings?

![snap11](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/d0177509-7fef-49a3-885c-7c0f4eab8f93)

Which day of the week has the best average ratings per branch?
![snap12](https://github.com/Ritvik-Srivastava/Walmart/assets/123249392/f55f3093-5a7a-4a6c-ba74-3288c2434331)
