# Amazon_Vine_Analysis
## Overview
 The overview of the analysis is to review the Amazon reviews written by members of the paid Amazon Vine program and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.
## Results
### Deliverable 1 Review
 - There were 9002021 reviews in the data set. After filtering for total votes greater than 20, there were 68164 remaining. There are 585 paid vine and 61139 unpaid vine reviews reviews that have a greater than 50% helpful_votes/total_votes. Among those 585 pain vine reviews, only 213 are five star. And out of the unpaid vine reviews, only 28839 have 5 star.
 - Out of the 68164 reviews, 42.31%' represents the percentage of five star review unpaid review and 0.31% represent the paid reviews.
### Images from PgAdmin
 - Customer Table
 - ![image](https://user-images.githubusercontent.com/107594143/193458730-d006f24c-b1bc-48de-9cf6-db2b79817632.png)
 - Products Table
 - ![image](https://user-images.githubusercontent.com/107594143/193458742-be531860-09d4-4cbc-bef2-5b8e9b2c33b1.png)
 - Review Table
 - ![image](https://user-images.githubusercontent.com/107594143/193458760-908a108a-d0a8-4e46-a61e-36585b964344.png)
 - Vine Table
 - ![image](https://user-images.githubusercontent.com/107594143/193458780-af2178d0-2598-4ea4-8380-35d9bcb74dde.png)

## Summary
