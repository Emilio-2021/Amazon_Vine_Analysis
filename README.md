# Amazon_Vine_Analysis
Analyzing Amazon reviews by members of its paid Amazon Vine program.

## Overview 
The purpose of the project is to analyze Amazon reviews written by members of the paid Amazon Vine program. In order to complete this analysis, I used a subset of data that pertained to the musical instruments subcategory of Amazon. 

The [Amazon Vine program](https://www.amazon.ca/gp/help/customer/display.html/?nodeId=GPEWN3RSQPEU2HST&pop-up=1) is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. 

## Results

During this analysis I wanted to answer a few key questions.

1. How many reviews were made and how many of those were Vine (paid) and Vine (unpaid)?
2. How many reviews were 5 stars? for paid and unpaid reviews?
3. What percentage of paid reviews were 5 stars? What percentage of non-paid reviews were 5 stars?

Here are my answers to these questions.

1. There are 14533 reviews where 60 were paid and 14473 unpaid.

![reviews](/pics/reviews.png)

2. There were 34 5-star vine reviews and 8210 5-star non-vine reviews for a total of 8244 5-star reviews.

![5StarsReviews](/pics/5StarsReviews.png)

3. 0.41% of paid reviews are 5-stars and 99.59% of unpaid reviews are 5-stars.

![porcentage5StarReviews](/pics/porcentage5StarReviews.PNG)

## Summary

After looking that the results, I would conclude that there is a positivity bias for reviews in the Vine program. It is important to note that while the non-vine sample size was very large, the vine sample size was less than 100 entries. 

In addition to the current analysis, I could take it a step further and see the percentage of those who purchased the product by filtering through the verified_purchase column to either confirm or fail to confirm if there is a positivity bias for reviews in the Vine program.