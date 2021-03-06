# Amazon_Vine_Analysis

## Overview of the analysis
The purpose of this analysis is to review the Amazon Vine Program and determine if there is a bias toward favorable reviews from Vine members.
The dataset used is from the Personal_Care_Appliances and was analyzed using PySpark to perform the ETL process to extract the dataset, transform the data, then connected to an AWS RDS instance.

## Results

## How many Vine reviews and non-Vine reviews were there?

o Vine reviews	
![Vine](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/vine%20reviews%20-%20paid.PNG)


o Non-Vine reviews
![Non-Vine](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/non-vine%20reviews%20-%20unpaid.PNG)


## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

o Vine 5-star reviews	
![Vine 5 star](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/vine%20reviews%20-%205%20stars.PNG)


o Non-Vine 5-star reviews	
![Non-Vine 5 star](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/non-vine%20reviews%20-%205%20stars.PNG)


## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

o Vine 5-star reviews percentage
![Vine 5-star percentage](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/vine%20reviews%20-%205%20stars%20percentage.PNG)


o Non-Vine 5-star reviews percentage
![Non-Vine 5-star percentage](https://github.com/amburu4159/Amazon_Vine_Analysis/blob/main/images/non-vine%20reviews%20-%205%20stars%20percentage.PNG)


## Summary 
There is a higher percentage of 5-star reviews (66%) for vine reviews vs 55% for non-vine reviews. Although the vine reviews are a small sample size, it does suggest that there is a positivity bias for reviews in the vine program

Another analysis to support the statement would be to analyze the mean, median and mode of the star rating for the Vine and non-Vine reviews.
