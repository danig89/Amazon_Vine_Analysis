# Amazon_Vine_Analysis

## Purpose
The purpose of this project was to analyze Amazon Music reviews written by members of the paid Amazon Vine program. The objectives were:
- Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
- Use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Resources
- Data Source: [Amazon Music Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz)
- Software: Google Colaboratory; Spark version 3.1.1; pgAdmin 4 version 4.29

## Results
### How many Vine reviews and non-Vine reviews were there?
Total Number of Vine Reviews: <b>7</b>
Total Number of non-Vine Reviews: <b>105,979</b>

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Number of Vine 5-star Reviews: <b>0</b>
Number of non-Vine 5-star Reviews: <b>67,580</b>

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Percentage of Vine 5-star reviews: <b>0</b>
Percentage of non-Vine 5-star reviews: <b>63.8%</b>

## Summary
