# Netflix Subscription Conjoint Analysis

This repository contains a hypothetical conjoint analysis study on Netflix subscription plans. The data is based on a forced-choice survey where respondents evaluated different subscription plans based on several attributes. Respondents were shown two hypothetical plans and had to select the preferable one.

## Project Overview

This analysis was completed as part of a bootcamp project created by Diogo Resende to gain experience using analytical tools in python. The goal was to understand how various features impact customer satisfaction and to identify the most valued attributes in a subscription plan.

## Survey Attributes

The survey included the following attributes:

1. **Number of Accounts**: 
   - Options: 1, 2, 3, 4, 5, 6

2. **Price**: 
   - Options: $8, $10, $12, $15, $18, $20

3. **Extra Content**: 
   - Options: 'HBO', 'Marvel', 'Disney', 'Soccer', 'Less Content', 'Prime Originals'

4. **Ads**: 
   - Options: 'one_per_day', 'one_per_show', 'none'

## Data and Analysis

The dataset represents fictional customer preferences collected through a forced-choice survey. The analysis includes calculating part-worth utilities for each attribute level to understand the impact of different features on customer satisfaction.

## Results

The analysis provided insights into customer preferences for Netflix subscription features based on the survey responses.

### Key Findings

1. **Number of Accounts**: 
   - The most important feature influencing customer decisions was the number of accounts. Customers valued the flexibility of having multiple accounts under one subscription.

2. **Price**: 
   - Price was the second most significant factor. Customers showed a strong preference for lower-priced plans, with significant negative impact observed for higher-priced plans.


3. **Extra Content and Ads**:
   - Content offerings such as 'HBO' and 'Marvel' were positively received, while less popular content, such as 'Soccer', had a negative impact.
   - Plans with no ads were strongly preferred, while ads shown per show had a significantly negative impact.

### Interaction Effects Analysis

To further explore customer preferences, an interaction term analysis was conducted. This revealed:

1. **Disney & One Ad per Day**:
   - The combination of Disney content with one ad per day had a large positive impact on customer satisfaction.

2. **HBO & One Ad per Day**:
   - Similarly, HBO combined with one ad per day was also a significant positive driver of customer preference.



These interactions suggest that while ads generally have a negative impact, pairing certain high-demand content with a limited number of ads can mitigate this effect and even lead to positive customer responses.

### Conclusion

This analysis highlights the critical role of the number of accounts and pricing in customer decision-making for Netflix subscriptions. The results can be used to optimize future subscription plans by balancing content offerings, ad frequency, and pricing to maximize customer satisfaction.


## Repository Contents

- `netflix_conjoint_analysis.ipynb`: The Jupyter Notebook containing the analysis.
- `netflix_customer_survey.csv`: The dataset used for the analysis.
- `README.md`: This file.

## Acknowledgements

This project was completed as part of a data science bootcamp, and the data is entirely hypothetical.
