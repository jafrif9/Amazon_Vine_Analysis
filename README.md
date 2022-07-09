# Amazon_Vine_Analysis

## Overview
The premise of the analysis was to determine if there is any bias towards favorable reviews from Amazon Vine members in a specified dataset. In order to complete the analysis PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. From there, PySpark was used to determine if a bias exists. For this analysis, the dataset pertaining to furniture products was used. 

## Results
The following is a summary of the results obtained from the analysis:
- From the total 792,113 reviews, 2,775 were from Amazon Vine members and 789,338 were from non-Amazon Vine members.
- Out of all the 5-star reviews, 1,356 were from Amazon Vine members and 446,360 were from non-Amazon Vine members; making a total of 447,716 5-star reviews.
<img width="533" alt="Screen Shot 2022-07-09 at 7 22 40 PM" src="https://user-images.githubusercontent.com/86126331/178125632-a230eefc-4ca4-4d3d-878a-9b319938a720.png">


- The analysis showed that 48.86% of the reviews from Amazon Vine members were 5-start reviews, and 56.55% of the reviews from non-Amazon Vine memebers were 5-star reviews.

## Summary
Upon initial view, it can be said that there is no positivity bias for reviews in the vine program. This is because both Amazon Vine members and non-Amazon vine members gave a 5-star review close to 50% of the time. However, it is important to note that reviews from Amazon Vine members made-up only 0.35% of the total reviews analyzed. Reviews from non-Amazon Vine members made-up 99.65% of the total reviews. Due to this disparity, it cannot confidently be sade that Amazon Vine members do not exibit a bias when writing 5-star reviews. In order to obtain a more accurate analyses, it is imperative that more reviews from Amazon Vine memebrs be taken, with there being a close to even distribution of Vine members and non-Vine members when completing the analysis.
