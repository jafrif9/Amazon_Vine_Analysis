# Amazon_Vine_Analysis

## Overview
The premise of the analysis was to determine if there is any bias towards favorable reviews from Amazon Vine members in a specified dataset. In order to complete the analysis PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. From there, PySpark was used to determine if a bias exists. For this analysis, the dataset pertaining to furniture products was used. 

## Results
The following is a summary of the results obtained from the analysis:
- From the total 792,113 reviews, 2,775 were from Amazon Vine members and 789,338 were from non-Amazon Vine members.
- Out of all the 5-star reviews, 1,356 were from Amazon Vine members and 446,360 were from non-Amazon Vine members; making a total of 447,716 5-star reviews.
- The analysis showed that 48.86% of the reviews from Amazon Vine members were 5-start reviews, and 56.55% of the reviews from non-Amazon Vine memebers were 5-star reviews.

## Summary

