# Project Overview

This project aims to analyze the Amazon Vine program and determine if there is a bias toward favorable reviews from Vine members.
I used PySpark to do the analysis by calculating different metrics, performing the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin. 
I focused on the US reviews in Electronics.

## Resources

•	Data Source:
 Amazon Review datasets: https://bootcampnnbigdatannpyspark.s3.amazonaws.com/amazon_reviews_us_Electronics_v1_00.tsv.gz
 
•	Software: Google Colab Notebook, PostgreSQL, pgAdmin 4, AWS(S3, RDB)

# Results

## Total number of reviews

•	Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Total_reviews_Paid_df.png)

•	Non-Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Total_review_Unpaid_df.png)

## Total number of 5-star reviews

•	Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Paid_5stars_count.png)

•	Non-Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Unpaid_5stars_count.png)

## Percentage of 5-star reviews

•	Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Paid_5stars_Percentage.png)

•	Non-Vine reviews

![](https://github.com/ALEIN3/Amazon_Vine_Analysis/blob/main/Images/Unpaid_5stars_Percentage.png)


# Summary

The analysis shows that 42% of the reviews in the Vine program were five-star reviews, whereas the percentage of the five-star reviews in the non-Vine reviews is only 46%. That means the reviews were close to reality, and there is no bias to give higher rate reviews for the Vine program.

We can apply some statistical analysis one that dataset like studying the measures of spread to define how the values distribute it among star levels.





