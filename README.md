# Customer Churn Dashboard – Tableau

Created by Nikhil Dev

## Project Summary

This Tableau project investigates patterns in customer churn using data from a telecom company. The objective is to uncover which types of customers are most likely to leave, and how factors like contract type, tenure, and services contribute to churn behavior.

🔗 **View the Interactive Dashboard**  
[Live on Tableau Public](https://public.tableau.com/...)

---

## Data Overview

**Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
**Size:** ~7,000 customer records  
**Features:** Demographics, billing info, subscription details, and churn status

---

## Business Challenge

Churn has a direct impact on revenue in any subscription model. This dashboard aims to answer:
- Which customers are most at risk of churn?
- How do service types, billing methods, or contract lengths affect churn rates?
- What can be done to retain high-risk segments?

---

## Visualizations Included

### 1. Churn by Contract Type
-  Month-to-month plans show the highest churn rate
-  Recommendation: Introduce incentives for long-term contracts

![Churn by Contract](https://github.com/nikhildevm/Customer_churn_tableau/blob/main/Churn%20Rate%20By%20Contract.png?raw=true)

---

### 2. Churn by Senior Citizen
-  Not-Seniors churn at a slightly higher rate
-  Recommendation: Offer better support for Younger users

![Churn by Senior](https://github.com/nikhildevm/Customer_churn_tableau/blob/main/Churn%20By%20Senior.png?raw=true)

---

### 3. Scatterplot: Monthly Charges vs Tenure
-  Many churned customers had low tenure but high bills
-  Recommendation: Focus retention campaigns on newer high-paying customers

![Charges vs Tenure Scatterplot](https://github.com/nikhildevm/Customer_churn_tableau/blob/main/Churn%20Charges%20VS%20Tenure.png?raw=true)

---

### 4. Interactive Dashboard Overview
- Includes dynamic filter for Contract Type
- Charts respond to user input for flexible exploration

![Dashboard Screenshot](https://github.com/nikhildevm/Customer_churn_tableau/blob/main/Dashboard.png?raw=true)

---

## Key Features

- Dashboard created using **Tableau Public**
- Filter controls for custom exploration
- Multiple charts tied together by shared business questions
- Clean layout designed for stakeholder communication

---

## Strategic Takeaways

- Push annual contracts over month-to-month to reduce churn
- Identify and intervene with new customers paying above-average charges
- Improve digital tools and support for non seniors
- Consider bundling additional services like tech support and backup

---

## Next Steps

- Extend analysis with churn prediction models using Python
- Build dashboards for product usage and retention campaign impact
- Embed Tableau dashboard in a reporting deck for executive use

---

## About the Author

I'm **Nikhil Dev**, a passionate Data Analyst about using data to solve customer and operations problems. My goal is to create visual insights that drive real business impact.


 Check out more work on [Tableau Public](https://public.tableau.com/app/profile/nikhil.dev.murali/)
