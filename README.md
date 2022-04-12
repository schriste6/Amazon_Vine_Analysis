# Amazon Vine Analysis
## Purpose:  
Using product reviews data from Amazon, perform analysis to determine if it is worthwhile to subscribe to a Vine Review Program. The Vine Review Program is an incentive model in which customers are 'paid' when they write reviews. 
### US Reviews Dataset:
    - Apparel (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Apparel_v1_00.tsv.gz)
### Technologies:
    - Google Colab / PySpark
    - Jupyter Notebook / Pandas
    - Amazon Web Service (AWS) and RDS and S3
    - PostgreSQL  
### Postgres query messages:  
![](/Images/products_table_sql_msg.png)
![](/Images/products_table_sql_msg.png)
![](/Images/review_id_table_sql_msg.png)
![](/Images/vine_table_sql_msg.png)

## Results:
- How many Vine reviews and non-Vine reviews were there?
![](/Images/vine_nonvine_reviews.png)
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![](/Images/vine_nonvine_5_star_reviews.png)
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![](/Images/vine_nonvine_pct_5_star_reviews.png)
## Summary: 
- Analysis does not support bias toward 5-star reviews by vine program reviwers.  

   - 5-Star reviews:
     - Vine reviewer:  45.5%
     - Non Vine reviewer:  52.3%
     
   - Additional data supports similar findings that reviews are similar between Vine and Non Vine reviewers.
   - Mean star rating:
     - Vine reviewer:  4.1 
     - Non Vine reviewer: 3.9
   ![](/Images/vine_nonvine_mean_stars.png)
