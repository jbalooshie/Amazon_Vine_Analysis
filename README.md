# Amazon_Vine_Analysis
## Overview of the analysis
The purpose of this analysis is to analyze Amazon reviews written by members of the paid Amazon Vine program. Companies listing their products on Amazon can pay a fee to have their products provided to individuals who are required to write a review. These individuals do not pay for the products, so it would be helpful to know if this creates an incentive to write a positive review. 

In this analysis, we take a dataset for a specific product category. We created several dataframes from the dataset to complete our analysis and uploaded them to a cloud database so it can be accessed by other stakeholders. From the dataframes, we drew conclusions, which are presented below. 

## Results
* There were 170 Vine reviews and 37840 non-Vine reviews
[Vine vs non-Vine totals](/images/image_1.PNG)

* There were 65 5 stars Vine reviews and 20612 5 stars non-Vine reviews. 
[5 stars Vine vs non-Vine](/images/image_2.PNG)

* 38.2% of the Vine reviews were 5 stars and 54.5% of the non-Vine reviews were 5 stars. 
[% of 5 stars Vine vs non-Vine](/images/image_3.PNG)

## Summary
### Potential for positivity bias
Based on the results of the analysis, there does not seem to be a pre-disposition for positivity bias amongst individuals writing Vine reviews. I found that 38.2% of the Vine reviews were 5 stars, while 54.5% of the non-Vine reviews were 5 stars. The main drawback to this analysis is the discrepancy in sample sizes. The number of non-Vine reviews is significantly larger than the number of Vine reviews (32,840 non-Vine vs 170 Vine reviews). 

### Additional analysis
One additional analysis that would be helpful here would be to perform the same investigation on another product category. This analysis was performed on a dataset of pet products. Selecting an unrelated dataset and performing the same analysis would allow us to see if there is a similar spread across both categories. If there are like ratios between Vine and non-Vine reviews in the second category, then that helps us control for the pet products category being an outlier.
