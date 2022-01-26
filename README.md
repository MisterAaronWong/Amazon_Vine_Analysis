# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review, though not all paid reviews are guaranteed to be 5 stars. For this particular analysis, the dataset of reviews for automotive parts were examined. PySpark was to the tool of choice used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. PySpark/Pandas was then used to determine if there were any biases toward favorable reviews from Vine members in the automotive reviews dataset.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions:
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?



## Summary
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

The summary states whether or not there is bias, and the results support this statement
An additional analysis is recommended to support the statement

You need following values - 
1. Total number of review 
2. Total number of 5 star review 
3. Percentage of 5 star reviews that are from paid users 
4. Percentage of 5 star reviews that are from unpaid users
