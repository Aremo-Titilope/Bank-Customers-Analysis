### Bank Customers Analysis

## Problem Statement
you have been provided with a dataset containing key demographic and finanacial details of bank customers. Your goal is to:

* analyze the dataset to gain insights into customer behaviour, financial standing, and engagement patterns.
* uncover valuable insights for the bank's decision making process
* identify trends and patterns in customer engagement
* highlighting potential areas for business improvement

## Objectives

* Get sales data

* Examine and profile

* Prepare for visualization

* Draw conclusions and recommendations


## Data Overview

The dataset contains several categories of customer information:

- Demographic Characteristics

* Age: Distribution of customers across different age groups

* Gender: Male vs. Female representation

* Geography: Customer distribution across regions

- Financial Characteristics

* Credit Score and assigned Credit Score Bracket (Poor, Fair, Good, Very Good, Excellent)

* Balance: Average customer account balance

* Estimated Salary: Customer income proxy

* Number of Products: Bank products (e.g., credit cards, loans) owned per customer

- Customer Engagement & Retention

* Tenure: Years of relationship with the bank

* IsActiveMember: Activity status indicator

* Exited: Whether the customer has left the bank (churn indicator)

### Insights  

Demographic Mix

* Middle age groups (25–34 and 35–44) generally have larger populations compared to younger (18–24) or older (65+) groups.

* Spain and Germany have particularly high counts in the 35–44 age group.

* In most countries and age groups, males (orange) are more numerous than females.

Engagement

* The chart shows a heavily skewed distribution where the majority fall into categories 1 and 2
* This suggests that geography-related representation is stronger among category 1.



Risk Ladders

* Highest Exit Rate in New Customers (0–1 years).
* Customers in the 2–3 year bracket show a significant drop in exit rate (to ~20.2%)



Churn 

* Customers with Poor credit scores have the highest exit rate (above 0.21)
* There is a slight downward trend as credit score improves
* Higher Exit Rates in Older and Youngest Groups
* Customers who are not active members have an exit rate of >25%.
* Customers with Fair credit scores have the highest estimated salaries (around 8).
* This reveals a disconnect between income and credit score quality,
having a higher salary doesn’t guarantee a better credit score, and vice versa. 


Finanacial Distribution

* Across all credit score brackets, balances are quite similar in distribution. This suggests credit score is not a strong differentiator of customer balance levels.
* Estimated salaries also show similar distributions across credit score brackets.
* Both balance and salary do not differ significantly across credit score categories. This implies credit score might be influenced more by customer behavior rather than raw income or deposit balances.



### Conclusions 

* At-Risk Customers Exist in Clear Segments
Customers who are inactive (IsActiveMember = 0) and/or hold ≤1 product show a disproportionately higher churn rate.

* Financial Exposure Is Concentrated
A meaningful share of estimated salary balances is held by these at-risk groups, particularly in certain Credit Score Brackets. Losing them would represent a measurable revenue/profit risk.

* Churn Drivers Are Multi-Dimensional
Churn correlates with credit score, age band, and tenure. Younger customers with poor credit, and older inactive customers with single products, are more prone to exit.

* Customer Engagement Is Uneven Across Geographies
Some regions show higher percentages of inactive customers, pointing to operational or service delivery gaps in specific geographies.



### Recommendations

- Prioritize Retention Programs for At-Risk Segments

* Launch proactive outreach (calls, tailored offers) for customers with less than one product and inactive status.

* Introduce loyalty incentives (fee waivers, bonus interest, bundled products).

- Increase Product Adoption

* Design cross-sell campaign like credit cards, savings plans etc targeted at single-product customers.

* Use personalized recommendations driven by customer profile and needs.

- Credit-Based Risk Mitigation

* Offer credit-building support (financial literacy programs, small-limit starter products) for customers in the “Poor” and “Fair” credit brackets.

* Retaining these groups protects long-term value and improves portfolio quality.

- Geographic Targeting

* Allocate branch or digital engagement resources in regions with above-average churn or inactivity.

* Consider piloting region-specific offers like community events, localized 


### Summary

If churn in inactive, single-product customers can be reduced even modestly, the bank can protect millions in estimated balances, improve product penetration, and stabilize long-term revenue streams.