# **Customer Churn Analysis Dashboard**
### This project analyzes customer retention for a telecom company, focusing on why customers churn and which factors influence retention. Using Power BI, interactive visualizations highlight key insights across demographics, contracts, payment methods, and service usage.

## **🚀Key Insights**

•	High churn is observed among customers with month-to-month contracts and shorter subscription durations.
•	Paperless billing is more common among churned customers.
•	Lack of additional services (like tech support or internet) correlates with higher churn.

## **📊Key Metrics?**

| Metric          | Total   | Churned | Churn Rate |
| --------------- | ------- | ------- | ---------- |
| Customer Count  | 7,032   | 1,869   | 26.6%      |
| Monthly Charges | $456.5K | $139.1K | 30.5%      |
| Yearly Charges  | $16.0M  | $2.8M   | 17.5%      |

## **📈Visualizations**

1. Demographics
Pie charts showing gender and senior citizen distributions:

Total Customers          | Churned Customers
♂ 49% | ♀ 51%            | ♂ 36% | ♀ 64% 
Senior: 16%              | Senior: 25%

2. Payment Methods
Bar charts comparing payment preferences:

Credit Card/Check:  25% → 28% ▲
Paperless Billing:  48% → 68% ⚠️
Electronic Check:   23% → 42% ⚠️
Mailed Check:       13% → 10% ▼

3. Subscription Tenure
Bar charts by subscription years:

Years 1-2:     ████████████ 55% churn peak
Years 3-5:     ███████     35% churn
Years 6+:      ███         10% churn

Insight: Highest churn risk in early lifecycle (1-2 years)

4. Contract Types
Pie chart distribution:

pie title Contract Types in Churn
    "Month-to-Month" : 54
    "One Year"       : 28
    "Two Year"       : 18

Key Finding: Month-to-month = 54% of all churn cases

5. Services Penetration
Pie charts showing service adoption gaps:

| Service          | Total | Churned | Gap     |
| ---------------- | ----- | ------- | ------- |
| Phone            | 90%   | 72%     | -18%    |
| Internet         | 52%   | 44%     | -8%     |
| Streaming TV     | 29%   | 22%     | -7%     |
| Streaming Movies | 27%   | 20%     | -7%     |
| Tech Support     | 29%   | 12%     | -17% ⚠️ |

## **🛠 Technologies Used**

•	Power BI – for creating interactive dashboards and charts
•	Telecom customer dataset – containing churn labels, demographics, contracts, payments, and service usage

