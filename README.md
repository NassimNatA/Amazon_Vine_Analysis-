# Amazon_Vine_Analysis

## Overview of the analysis: 

The purpose of this analsis is to execute the ETL process on an Amazon review dataset to to extract the dataset, transform the data, connect to an AWS RDS instance. In addition, this project uses PySpark and SQL to determine if the bias exists towards favorable reviews. 

## Results:
- How many Vine reviews and non-Vine reviews were there?
![alt_text](https://github.com/NassimNatA/Amazon_Vine_Analysis-/blob/main/Screen%20Shot%202021-01-10%20at%201.05.19%20AM.png)

Using the code shown above, 463 were Vine reviews and 25094 reivews were non-Vine. 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![alt_text](https://github.com/NassimNatA/Amazon_Vine_Analysis-/blob/main/Screen%20Shot%202021-01-10%20at%201.05.48%20AM.png)

Using the code shown above, 202 Vine reviews were 5 sars and 12033 nonVine reviews were stars.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![alt_text](https://github.com/NassimNatA/Amazon_Vine_Analysis-/blob/main/Screen%20Shot%202021-01-10%20at%201.08.14%20AM.png)

Using the code shown above, 43% of Vine reviews were 5 stars and 48% of non-Vine reviews were 5 stars. 


##Summary
- Total Summary Statistics
![alt_text](https://github.com/NassimNatA/Amazon_Vine_Analysis-/blob/main/TotalSummary.png)

Based on the data analysis shown above, is there is not a significant bias for Vine vs. Non-Vine reviews having 5 star ratings. As shown in the summary table above and in the results, the two types of reviews were within 5% of each other for 5-star ratings. However, it is notable that there was a much larger distribution of non-Vine reviews (25094) compared to Vine reviews (463) for this dataset. Additional analysis recommended would be to deep-dive into the categories with Vine vs. Non-Vine reviews, for example: how many products from Vine-reviewed category were purchased vs. number of products purchased from Non-Vine reivewed category. This will help determine if these reviewes have a strong influence in customer discretion in purchasing the products. 
