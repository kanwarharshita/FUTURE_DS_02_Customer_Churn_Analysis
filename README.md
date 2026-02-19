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

| Category | Total Customers | Churned Customers |
| -------- | --------------- | ----------------- |
| Male     | 49% ♂           | 36% ♂             |
| Female   | 51% ♀           | 64% ♀             |
| Senior   | 16%             | 25%               |

2. Payment Methods
Bar charts comparing payment preferences:

{
  "type": "bar",
  "data": {
    "labels": ["Credit/Check", "Paperless", "E-Check", "Mailed"],
    "datasets": [{
      "label": "Total",
      "data": [25, 48, 23, 13],
      "backgroundColor": "rgba(54,162,235,0.6)"
    }, {
      "label": "Churned",
      "data": [28, 68, 42, 10],
      "backgroundColor": "rgba(255,99,132,0.6)"
    }]
  }
}


3. Subscription Tenure
Bar charts by subscription years:

1-2 Years: ████████████ 55% (Peak Churn)
3-5 Years: ███████     35%
6+ Years:  ███         10%

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

