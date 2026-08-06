# 📊 RavenStack Customer Retention & Churn Analysis

## 📌 Project Overview

This project analyzes customer retention and churn for **RavenStack**, a SaaS subscription business.

The objective of this analysis is to understand why customers leave, identify customer segments with higher churn risk, analyze customer lifetime and retention patterns, and provide actionable business recommendations to improve customer retention.

The project combines customer account, subscription, feature usage, churn event, and support ticket data to create a complete customer retention analysis.

---

## 🎯 Business Objectives

The analysis focuses on answering the following questions:

* What is the overall customer churn rate?
* Which customer segments are most likely to churn?
* Which acquisition channels have better customer retention?
* What are the main reasons customers leave?
* How long do customers typically remain active?
* How does retention vary across customer cohorts?
* What actions could help reduce customer churn?

---

## 📂 Datasets

The project uses five datasets:

| Dataset                          | Description                                                           |
| -------------------------------- | --------------------------------------------------------------------- |
| `ravenstack_accounts.csv`        | Customer account, industry, country, signup, and churn information    |
| `ravenstack_subscriptions.csv`   | Subscription plans, MRR, upgrades, and downgrades                     |
| `ravenstack_feature_usage.csv`   | Customer product usage and engagement                                 |
| `ravenstack_churn_events.csv`    | Customer churn events and reasons                                     |
| `ravenstack_support_tickets.csv` | Support interactions, resolution times, satisfaction, and escalations |

The datasets were combined at the customer/account level to create a unified analytical view.

---

## 🛠️ Tools Used

* **Microsoft Excel**
* Excel formulas and calculations
* Data cleaning and transformation
* Customer segmentation
* Cohort analysis
* Data visualization
* Dashboard development
* Business insight generation

---

## 🧹 Data Preparation

The raw datasets were cleaned and organized before analysis.

Key preparation steps included:

* Checking for missing and inconsistent values
* Standardizing boolean and categorical fields
* Converting date columns into appropriate date formats
* Connecting datasets using account and subscription IDs
* Aggregating feature usage at the account level
* Aggregating support ticket metrics at the account level
* Creating customer lifetime/tenure metrics
* Creating signup-month cohorts
* Creating a unified account-level analytical dataset

---

## 📊 Excel Dashboard

The complete customer retention and churn analysis was developed in **Microsoft Excel**.

The workbook includes:

* Executive Dashboard
* Account-Level Analysis
* Customer Segmentation
* Signup Cohort Analysis
* Customer Lifetime Analysis
* Churn Reason Analysis
* Active MRR metrics
* Business insights and recommendations

The complete workbook is available in this repository:

**`ravenstack_retention_analysis.xlsx`**

---

## 📈 Key Results

### Overall Customer Churn

* **Total Customers:** 500
* **Churned Customers:** 110
* **Retained Customers:** 390
* **Overall Churn Rate:** 22.0%
* **Median Customer Lifetime:** ~298 days

The results show that approximately one in five customer accounts in the dataset are classified as churned.

---

## 🔍 Key Insights

### 1. DevTools Customers Show Higher Churn

The **DevTools** customer segment has a churn rate of approximately **31%**, making it one of the highest-risk industry segments in the dataset.

This suggests that RavenStack should investigate the onboarding experience, product fit, feature adoption, and customer-success needs of DevTools customers.

---

### 2. Acquisition Channel Affects Retention

Customer churn differs significantly depending on acquisition source.

Approximate churn rates include:

| Acquisition Source | Churn Rate |
| ------------------ | ---------: |
| Partner            |      14.6% |
| Organic            |      17.5% |
| Ads                |      23.5% |
| Other              |      24.3% |
| Event              |      30.2% |

Customers acquired through **events** show substantially higher churn than customers acquired through partner and organic channels.

This may indicate differences in customer quality, expectations, or product fit across acquisition channels.

---

### 3. Multiple Factors Contribute to Churn

Important recorded churn reasons include:

| Churn Reason | Accounts |
| ------------ | -------: |
| Budget       |       17 |
| Pricing      |       16 |
| Features     |       15 |
| Support      |       14 |
| Competitor   |        7 |
| Unknown      |        6 |

The results suggest that customer churn is not caused by one single issue.

Product capabilities, customer support, pricing, and customer budget constraints all appear to play a role.

---

### 4. Customer Lifetime Provides Retention Context

The median customer lifetime is approximately **298 days**.

Customer lifetime analysis can help identify when customers are most vulnerable to churn and where retention interventions may have the greatest impact.

---

## 👥 Customer Segmentation

Customers were segmented using characteristics such as:

* Industry
* Plan tier
* Country
* Referral/acquisition source
* Trial status

This analysis helps identify groups that require more targeted retention strategies.

Rather than applying the same retention strategy to every customer, RavenStack can focus resources on higher-risk segments.

---

## 📅 Cohort Analysis

Customers were grouped according to their **signup month** to evaluate retention across different customer cohorts.

The cohort analysis includes:

* Number of customers acquired
* Number of customers churned
* Number of retained customers
* Retention rate

This provides a view of how customer retention changes across different signup periods.

---

## ⏳ Customer Lifetime Analysis

Customer tenure was calculated using the customer's signup date and either their churn date or the analysis end date.

This metric helps evaluate how long customers typically remain with RavenStack before leaving.

Customer lifetime can also be analyzed alongside:

* Industry
* Plan
* Acquisition source
* Product engagement
* Support activity
* Churn reason

---

## 💡 Business Recommendations

### 1. Develop a DevTools Retention Strategy

Create targeted onboarding, product-adoption, and customer-success initiatives for DevTools customers because this segment shows particularly high churn.

### 2. Review Event-Based Acquisition

Investigate why event-acquired customers have higher churn.

RavenStack could improve customer qualification and expectation-setting before converting event leads into paying customers.

### 3. Improve Trial-to-Paid Onboarding

Define clear activation milestones during the early customer lifecycle and proactively engage customers who fail to reach those milestones.

### 4. Address Product Feature Gaps

Review feature-related churn feedback and compare it with feature-usage data to identify product improvements that could have the greatest retention impact.

### 5. Improve Customer Support

Identify customers with repeated support issues, long resolution times, low satisfaction, or escalations and provide proactive customer-success intervention.

### 6. Introduce Retention and Downgrade Options

For customers considering cancellation because of pricing or budget constraints, provide appropriate downgrade paths or alternative plans where commercially viable.

---

## 📁 Repository Structure

```text
ravenstack-customer-retention-analysis/
│
├── README.md
│
├── ravenstack_retention_analysis.xlsx
│
├── ravenstack_accounts.csv
├── ravenstack_subscriptions.csv
├── ravenstack_feature_usage.csv
├── ravenstack_churn_events.csv
└── ravenstack_support_tickets.csv
```

---

## 📁 Project Files

| File                                 | Description                               |
| ------------------------------------ | ----------------------------------------- |
| `ravenstack_retention_analysis.xlsx` | Complete Excel analysis and dashboard     |
| `ravenstack_accounts.csv`            | Customer account data                     |
| `ravenstack_subscriptions.csv`       | Subscription and MRR data                 |
| `ravenstack_feature_usage.csv`       | Product engagement and feature usage data |
| `ravenstack_churn_events.csv`        | Churn events and customer churn reasons   |
| `ravenstack_support_tickets.csv`     | Customer support and satisfaction data    |

---

## 🚀 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Customer Churn Analysis
* Customer Retention Analysis
* Customer Segmentation
* Cohort Analysis
* Customer Lifetime Analysis
* SaaS Analytics
* Excel Dashboard Development
* Data Visualization
* Business Insight Generation
* Data-Driven Decision Making

---

## 📌 Conclusion

The analysis found an overall customer churn rate of **22%**.

Churn is not evenly distributed across RavenStack's customer base. DevTools customers and event-acquired customers represent particularly important retention opportunities.

Churn feedback also highlights budget, pricing, feature gaps, and customer support as important areas requiring attention.

By combining customer segmentation, churn feedback, customer lifetime, product engagement, and support data, RavenStack can develop more targeted retention strategies and focus resources on customers with the greatest churn risk.
