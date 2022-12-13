# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. I use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results
<img width="500" alt="Screen Shot 2022-12-13 at 1 57 50 AM" src="https://user-images.githubusercontent.com/107594280/207286709-87cadc6a-e0bd-4fb8-8d15-fec8343eb084.png">




**1. How many Vine reviews and non-Vine reviews were there?**

There were 33 Vine reviews and 45,388 non-Vine reviews. This means that only .07% of the reviews were Vine reviews.


**2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

15 Vine reviews where 5 stars and 23,733 non-Vine reviews were 5 stars.


**3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

45% of Vine reviews were 5 stars whereas 52% of non-vine reviews were 5 stars.

## Summary
THe data may suggest that there doesn't seem to be a bias towards paid reviews. However, the sample size for Vine reviews was a lot smaller than non-Vine reviews, so further analysis would need to be done. For example, we could look at the other Amazon categories to see if this pattern continues across other datasets.
