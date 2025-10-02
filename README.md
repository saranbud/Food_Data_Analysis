# Marketing Campaign Analysis for Food Company
## Introduction
### Overview
Our food company decided to test the waters with a direct marketing campaign, hoping to turn some profit magic. The pilot involved 2,240 customers. Out of those, only 15 percent actually purchased the offer. The campaign cost 6,720MU but only generated 3,674MU in revenue, leaving a loss of 3,046MU. Not exactly a victory, but a treasure trove of lessons for our next moves.

## Goal
The main mission is to predict which customers are likely to buy and then scale that knowledge to the rest of the customer base. The Chief Marketing Officer is also curious about the type of customers who are most responsive so future campaigns are smarter and more profitable.

## Insights from the Analysis
Our Random Forest model did a solid job, correctly identifying 72 percent of the customers who would actually respond. That’s a promising start for refining future campaigns.

From the data, we learned a few things about who’s more likely to say yes:
Customers with recent purchases and high total spending, especially those above 2,000MU
Middle-class earners with incomes roughly between 53,000 and 107,000MU
Loyal customers who have been around for a while and responded to past campaigns, particularly campaigns one, two, three, and five
Younger customers under 25 and those without dependents
Shoppers who prefer web or catalog purchases
Single, divorced, or widowed customers seem more open to offers
On the flip side, married customers and those with lower education levels, such as Basic or 2nd Cycle, were less responsive.

## Statistical Takeaways
ANOVA and chi-square tests revealed that predictors like Income, Recency, Customer Days, Dependencies, MntTotal, and NumWebPurchases significantly affect the likelihood of purchase. These are the heavy hitters to focus on in targeting and modeling. Other variables, like NumDealsPurchases, were less useful and showed little impact.

## Next Steps for Smarter Campaigns

Experiment with other machine learning models such as logistic regression or decision trees for better accuracy and insights

Create new features from existing data, such as combining purchasing patterns or previous campaign responses, to improve predictions

Segment customers into meaningful groups and tailor offers and messaging for each segment

Run a cost-benefit analysis to understand the potential return on investment and make smarter budgeting decisions

## Dataset
This analysis used data sourced from Kaggle: https://www.kaggle.com/datasets/jackdaoud/marketing-data

## How to Use This Project

Clone the repository to your local machine.
Load the dataset and perform exploratory data analysis.
Build classification models to predict customer behavior.
Analyze results to identify key customer segments.
Use insights to design optimized marketing campaigns.

### Authors
Saranya Srija Buddhavarapu
