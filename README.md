# Amazon_Vine_Analysis

## Overview of the Analysis
I have chosen Video Games Data from Amazon reviews for this project and utilized Pyspark to perform the ETL process by extracting, transforming the data and connecting the database through the AWS webserver. From the reviews, my aim is to determine of there is any bias towards reviews from the Vine members of our dataset. 

## Results

### How many Vine reviews and non-Vine reviews were there?
- Total number of Vine reviews: 94
!(https://user-images.githubusercontent.com/93291994/165455854-8b0ea3a0-cc5c-4249-bbeb-415272b56dd7.png)

- Total number of Non - Vine reviews: 40471
!(https://user-images.githubusercontent.com/93291994/165456275-2d08f4ec-0808-4f3c-b9a2-0e3853a26d84.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Total number of Vine Five-Star reviews is 48.
- Total of Non-Vine Five-Star reviews: 15663
!(https://user-images.githubusercontent.com/93291994/165456728-e788db0a-89f5-4783-bee4-33e4c8af7eff.png)

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Total percentage of Vine Five-Star reviews: 51%
- Total percentage of Non-Vine Five-Star reviews: 39%
!(https://user-images.githubusercontent.com/93291994/165457075-4dd003ea-329a-4d50-a58f-c7831ed26beb.png)

## Summary 
From the analysis, it can be concluded that there is a possibility of bias as 51% of the Amazon reviews that were a part of the Vine program who gave 5-star rating, compared to only 39% of the Amzon reviews who were not a part of the Vine program also gave 5-star ratings. 

## Resources
Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz
Sofware: Python, PostgreSQL, pgAdmin, Google Colab Notebook, AWS
