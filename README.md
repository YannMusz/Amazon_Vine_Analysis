# Amazon_Vine_Analysis
Big Data using PySpark, Amazon Web Service (AWS), Google Colaboratory, and pgAdmin

## Overview of the Analysis
Some natural language processing skills were explored to prepare a customer review analysis

## Some Topics Explored
1. Define big data and describe the challenges associated with it.
2. understand Hadoop and name the main elements of its ecosystem.
3. show how MapReduce processes data.
4. Define Spark and explain how it processes data.
5. Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
6. Complete an analysis of an Amazon customer review.

## Example
Example of AWS data pulled into pgAdmin
     
![Pic 1](https://github.com/YannMusz/Amazon_Vine_Analysis/blob/main/Images/dev1_customer_table.PNG)

## Results

### Number of vine and non vine reviews
Data set seeems limited for Big Data with only 145,431 reviews.
Only reviews with 20 or more votes where considered for the rest of the analysis
Helpful votes were defined as being 50% or greater than the total votes narrowing the list to 1,685 reviews.

The applied criterie greatly reduced the sample size.  In the remainder 1,685 reviews, there were no reviews that were paid 

![Pic 2](https://github.com/YannMusz/Amazon_Vine_Analysis/blob/main/Images/dev2_count_is_zero.PNG)     

All 1,656 remaining reviews are unpaid Vine with 0 paid Vine.  

### Number of Vine and non vine 5 star Reviews 
 631 Unpaid vine reviews reviews. There are also 0 paid Vine with 5-star reviews.     

### Percentage of Vine reviews with 5 Star and percentage of von-Vine reviews with 5 stars
![Pic 3](https://github.com/YannMusz/Amazon_Vine_Analysis/blob/main/Images/dev2_vine_reviews_no.PNG)   
The percentage of unpaid, 5-star Vine reviews resulted in 37.4%, while the percentage of paid, 5-star Vine reviews would be 0%.   

## Summary
It was hard to compare paid and unpaid due to the small sample size and seems more biased towards unpaid reviews.
The starting criteria of 20 likes or the 50% helpful criteria may have been too high, which made the data set too small.  Changing the filtering criteria to expand the sample size wouldve helped with a more non biased approach. 
