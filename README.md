# E-Commerce-Customer-Churn-Engagement-Analytics
## Dataset Overview

The dataset customer_churn1 contains customer-level information for an e-commerce platform, including demographics, transaction behavior, engagement metrics, complaints, order history, payment preferences, and churn status. It is designed to analyze customer retention, engagement patterns, and churn drivers.

## Objectives

Analyze customer churn patterns and identify at-risk segments.

Understand behavioral and transactional factors affecting churn.

Generate actionable insights for marketing, onboarding, and retention strategies.

Explore payment preferences, order behavior, and coupon usage to improve engagement.

## Tools and Technologies Used

SQL (MySQL) – Data querying, aggregation, and analysis.

## Key Insights

Overall churn rate is ~16.8%.

Complaints correlate strongly with churn:

Complain=1 → 31.67% churn

Complain=0 → 10.93% churn

Churn is highest among new customers (Tenure 0–1 month, ~50–53%).

Login device impact: Computer users churn higher (19.83%) than Mobile (~15.62%).

Higher-order segments consume more coupons per customer.

Payment modes: Debit Card most used (2314 customers), followed by Credit Card (1774).

Behavioral factors like hours spent on app show minimal effect alone on churn.

## Conclusion

Customer churn is primarily driven by early lifecycle risk (low tenure) and service failure signals (complaints). Secondary factors like login device, order activity, and coupon usage provide further segmentation insights.

Recommended strategy: Focus on first-week onboarding, rapid complaint resolution, and targeted retention interventions based on engagement and transactional patterns to reduce churn and improve customer loyalty.
