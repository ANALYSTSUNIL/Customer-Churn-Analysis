# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview
This project focuses on identifying and analyzing customer churn patterns within a telecom company. By exploring demographic data, 
service usage, contract structures, and payment behaviors, this analysis uncovers critical drivers of customer attrition and 
provides strategic, data-backed retention solutions.

---

## 🛑 Problems
The primary challenge addressed in this project is high customer attrition (churn), which impacts business revenue and growth. 
Specific underlying problems discovered include:
* High Early Attrition: Significant customer loss during the initial onboarding phase.
* Contract Vulnerability: Extreme churn risk associated with flexible, short-term commitments.
* Service Disconnection: Disproportionate churn among high-tier service users and those lacking additional support services.
* Billing Friction: Elevated churn tied to specific high-effort manual payment channels.

---

## 🛠️ Tools
* Excel / Power Query: For initial data cleaning, transformation, and structural preprocessing.
* Python / Pandas/ Matpltlib / Seaborn 

---

## 🔍 Analysis
The analysis explores multiple customer touchpoints to gauge churn risk systematically across five major areas:
1. Demographic Analysis: Comparing churn velocity between senior citizens and non-senior customer segments.
2. Tenure & Contract Lifecycle: Evaluation of churn rates against customer relationship duration and contract commitments (Month-to-Month vs. Long-Term).
3. Product & Service Ecosystem: Investigating core internet types (Fiber Optic vs. DSL) and the retention impact of value-added service bundles.
4. Financial Metrics: Assessing customer sensitivity to higher monthly bill thresholds (>70).
5. Transactional Channels: Analyzing how friction-heavy payment methods correlate with overall customer attrition.

---

## 💡 Insights
* Demographics: Senior citizens show a significantly higher churn rate (40–45%) compared to non-senior customers (25–30%).
* Tenure: Attrition peaks heavily at 0–2 months (~50–60% churn), but drops sharply to 10–15% once a customer crosses the 24-month loyalty milestone.
* Contract Types: Month-to-month contracts are the strongest indicator of churn (~40–45%), whereas 2-year contracts show the highest stability (~5–10% churn).
* Internet Infrastructure: Surprisingly, Fiber Optic users experience the highest churn segment (40%+), suggesting potential issues with pricing expectations or service quality.
* Service Add-ons: Customers missing value-added services have massive churn rates (~35-40%), which drops down drastically to 15–20% when Online Security, Backup, or Device Protection is active.
* Payment Methods: Electronic check payers exhibit the worst churn behavior (~45%), signaling high billing friction or poor engagement.
* Monthly Charges: Financial sensitivity is apparent, as customers with premium monthly bills exceeding 70 show a noticeably high churn trend.

---

## 🎯 Actionable Recommendations
To mitigate attrition and boost customer lifetime value, the company should implement the following targeted strategies:

* Encourage Long-Term Contracts: Design aggressive incentives, discounts, or loyalty perks to transition vulnerable month-to-month users into stable 1-year or 2-year agreements.
* Bundle Security and Protection Services: Standardize product configurations by bundling Online Security, Online Backup, and Device Protection directly into core packages to artificially improve retention floors.
* Optimize New Customer Onboarding: Overhaul the critical 0–2 month customer lifecycle window with dedicated customer support check-ins, tutorials, and clear value messaging to combat early-stage churn.
* Audit Fiber Service Infrastructure: Review the competitive market pricing and baseline connection quality of the Fiber Optic service to resolve why high-paying tech customers are leaving.
* Promote Automated Payment Channels: Run marketing and operational campaigns offering minor billing credits to shift Electronic Check users toward low-friction Auto-Payment channels (Bank Transfers or Credit Cards).
