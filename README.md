# Amazon Vine Analysis
## Purpose:
Analyzing Amazon reviews written by members of the paid Amazon Vine program, The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products, using PySpark. Main tasks are to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin and determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results:
* Total number of Vine reviews were 613 and non-Vine reviews were 64,968.
* Total 5 starts Vine reviews were 222 and non-Vine 5 stars reviews were 30,543.
* Percentage of 5 stars Vine reviews was 36% and percentage of 5 stars non-Vine reviews was 47%.

## Summary: 
As we can see from the above results, there is no positivity bias for reviews in the Vine program. The analysis result shows that percentage of vine members who give 5 star rating is lower than non-members percentage. An additional analysis to the dataset to support this statement is the following:
* Comparing the result of 4 and 5 stars rating for paid vs unpaid review.
