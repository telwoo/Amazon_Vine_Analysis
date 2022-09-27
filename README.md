# Amazon_Vine_Analysis

## Overview of the analysis: 
the main purpose was to pick a dataset (I selected amazon shoe review) and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results: 
- How many Vine reviews and non-Vine reviews were there? There were 22 vine reviews, of the 22, 15 had 5 start reviews. There weere 26924 non-vine reviews, of which 14439 had 5 start reviews. See image below with further stats.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? See below chart for details on this matter. Total vine reviews were 22, total non-vine reviews were 26,924.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 59% of vine reviews were 5 star!

![5star](https://user-images.githubusercontent.com/106715923/192407856-46a60c86-6165-4ceb-a605-102eefbc55f3.png)


## Summary: 
Overall, there appeared to be an even bias between the two different types of reviews. There were more non-vine related reviews, therefore so of making the data appear more skewed. However, there was a large turnout for reviews in the first place. One additional anlysis that would be beneficial would be to determine the overall marketplace in which the shoes were solid within different countries, outside of the US. 
