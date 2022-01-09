# Amazon_Vine_Analysis

## Overview
The purpose of the analysis is to determine whether being paid by Vine or not favorably influences the star-ratings in the reviews.

## Results
![vine_reviews_table](https://github.com/hwaijiinlee/Amazon_Vine_Analysis/blob/main/Resources/vine_reviews_table.png)

- There were a total of 14,537 reviews, out of which 60 were Vine reviews and 14,477 were non-Vine reviews
- Out of the 60 Vine reviews, 34 or 56.7% were 5-stars 
- Out of the 14,477 non-Vine reviews, 8,212 or 56.7% were 5-stars

## Summary
Based on the above analysis, there does not appear to be any positivity bias for reviews paid by Vine as the percentage of 5 star ratings for both Vine and non-Vine reviews were the same at 56.7%.

An additional analysis that we can do is to further filter the dataset by verified_purchase == "Y". This way, we can determine as well that the star ratings are provided at least with product in-hand.

Having said that, the number of Vine reviews for this dataset is so small that the conclusion drawn may not be entirely accurate. 



