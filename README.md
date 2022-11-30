# Amazon_Vine_Analysis
## Overview
The purpose of this project is to provide analytics to an Amazon review program by performing ETL to a data set and uploading it into a SQL data base and performing analysis on the resulting dataframe.
## Results
![reviews](https://github.com/pmercado625/Amazon_Vine_Analysis/blob/main/reviews_analysis.png?raw=true)  
Above is a snippet from the analysis code used to analyze the reviews for the paid and unpaid reviews, respectively.  
- For the paid reviews, there were 48 5 star reviewsout of the total 94 reviews, meaning ~51% of these reviews were 5 star reviews.  
- For the unpaid reviews, there were 15,663 5 star reviews out of 40,471 total reviews, meaning ~39% of the reviews were 5 star reviews.
## Summary
In this analysis, we examined the differences in reviews between people who did participate in Amazon's vine program (paid) and people who did not participate (unpaid). Through this analysis we were able to draw possible conclusions about biases:
- The paid reviews had more positive (5 star) reviews, percentage-wise. This could be attributed to the fact that there was monetary compensation (or just any compensation) involved within creating the reviews. This could serve as possible motivation and would posit the reviewer to be in a friendlier/more satisfied mood when creating the review.
- The unpaid reviews were as stated, unpaid. Therefore, there was no particular incentive to offer good reviews. It's entirely possible that these reviews are more critical and receptive to possible negative aspects during the review process.
-------------------------------------------------------------------------------
Future Improvements -  
An additional analysis that could provide more insight in this analysis would be to examine the verified purchases of the reviewer. This is because reviews could be given without the product being tested (such as through hearsay or other people's reviews). As such, these reviews could be removed from reviewers that actually purchased said product and an evaluation with better integrity could be conducted. Additionally this separation could also be used as it's own bias question (are the reviews from the verified purchases be better/worse on average than the unverified purchases?)
