# Amazon_Vine_Analysis
## Overview
Evaluate reviews of outdoor items sold on Amazon to see if Vine users who were paid to review a product are more likely to give a higher review than customers who didn't participate in the Vine program.
## Project Plan
I pulled in the review set from amazon. Split the original dataset into 4 dataframe in 4 dataframes.
From the vine dataframe I removed reviews that were poorly rated (had less than 20 votes) and those that weren't deemed helpful by Amazon customers (less than a 50% helpfulness rating.  

## Results
Number of Reviews:
*  Vine Reviews: 107
*  Non-Vine Reviews: 39,869

5 Star Reviews:
*  Vine: 56
*  Non-Vine: 21,005

Percentage of 5 Star Reviews:
*  Vine: 52.34%
*  Non-Vine: 52.69%

![Results](https://user-images.githubusercontent.com/86027932/136732826-766d71bd-9e94-4bec-8b5a-d266c06ae1fe.png)


## Summary
From the above results is doesn't appear that there is a positivity bias for reviews in the Vine program for items classified as "Outdoor". The rate of 5 star reviews is comperable between Vine and non-Vine customers. 
