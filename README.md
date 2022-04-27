# Amazon_Vine_Analysis

## Overview of the Analysis
I have chosen Video Games Data from Amazon reviews for this project and utilized Pyspark to perform the ETL process by extracting, transforming the data and connecting the database through the AWS webserver. From the reviews, my aim is to determine of there is any bias towards reviews from the Vine members of our dataset. 

## Results

### How many Vine reviews and non-Vine reviews were there?
- Total number of Vine reviews: 94
![Screen Shot 2022-04-27 at 2 32 04 AM](https://user-images.githubusercontent.com/93291994/165458967-89ed8c25-bd05-4532-9a12-b79179126c2a.png)

- Total number of Non - Vine reviews: 40471
![Screen Shot 2022-04-27 at 2 35 09 AM](https://user-images.githubusercontent.com/93291994/165459004-e12176cb-696e-43e5-8385-5ca800a4522a.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Total number of Vine Five-Star reviews is 48.
- Total of Non-Vine Five-Star reviews: 15663
![Screen Shot 2022-04-27 at 2 38 02 AM](https://user-images.githubusercontent.com/93291994/165459074-59072bf0-9d8c-46ca-be60-276563db2e01.png))

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Total percentage of Vine Five-Star reviews: 51%
- Total percentage of Non-Vine Five-Star reviews: 39%
![Screen Shot 2022-04-27 at 2 40 43 AM](https://user-images.githubusercontent.com/93291994/165459108-aca8fd49-080f-43b7-8c7b-8d1be1cff215.png)

## Summary 
From the analysis, it can be concluded that there is a possibility of bias as 51% of the Amazon reviews that were a part of the Vine program who gave 5-star rating, compared to only 39% of the Amzon reviews who were not a part of the Vine program also gave 5-star ratings. 

## Resources
Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz
Sofware: Python, PostgreSQL, pgAdmin, Google Colab Notebook, AWS
