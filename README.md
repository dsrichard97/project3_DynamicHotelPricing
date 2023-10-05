# project4: Dynamic Hotel Pricing and Customer Segmentation using Machine Learning
* Collaborators: Richard Diazdeleon
* Date: October 5. 2023


## Introduction
We use detailed data on 4,599 hotels located in Rome collected from TripAdvisor, the
world's largest travel platform, to examine the effects of
bubble ratings (detailed to half-
bubbles) on hotel popularity measured by the number of people viewing the hotel’s page.
By using a regression discontinuity design, we find that the bubble presentation of ratings
does not create any significant jumps at cutoffs. This result is different from those obtained
in previous studies of similarly designed rating systems from other industries. We provide
possible explanations and implications of this result. Another finding is that web users tend
to shortlist hotels with a bubble rating of at least 3. Despite that, there is no compelling
evidence of review manipulation around the cutoff of 2.75 to make a transition from the 2.5-
bubble rating to the 3-bubble rating. Potential uses of the number of views as a proxy of
demand in hospitality research are outlined.

## Research Questions
* 1. How can dynamic pricing strategies be optimized for different segments of hotels?
* 2. What are the key features that significantly influence hotel pricing?
* 3. Can machine learning models accurately segment hotels based on dynamic pricing?

## Methodology
* Data Exploration:
a. Fetch and clean the hotel dataset including features like customer ratings, views, and amenities.
b. Perform exploratory data analysis to understand trends, seasonality, and feature importance.

* Statistical Models:
a. Apply Decision Tree and Naive Bayes classifiers for hotel segmentation.
b. Analyze feature importance to identify the key drivers of hotel pricing.

* Model Evaluation:
a. Evaluate the models using accuracy, precision, and recall metrics.
b. Interpret the results in the context of marketing strategies for different segments.
 
## Key Findings
Decision Trees provided a higher accuracy in segmentation compared to Naive Bayes.
Features such as score_adjusted and location_grade are critical in determining hotel pricing.

##  R Code and Libraries Used
* Python Version: 3
* Libraries: pandas, scikit-learn, matplotlib, seaborn
  
## Future Work
Recreate the different marketing strategies: Reputation Mangement, Promotions and Discounts, Geo-Targeting.

## References

Analysis: [
](https://github.com/dsrichard97/project4DynamicHotelPricing/blob/main/Trip%20Advisor%20Marketing%20Analysis.pdf)
Kaggle Link: [
](https://www.kaggle.com/datasets/jocelyndumlao/tripadvisor-rating-impact-on-hotel-popularity)https://www.kaggle.com/datasets/jocelyndumlao/tripadvisor-rating-impact-on-hotel-popularity

