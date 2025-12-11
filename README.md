📊 Customer Churn Strategy & Retention Optimization Project
End-to-End Analytics | Feature Engineering | Predictive Modeling | Revenue Impact | Tableau Storyboard
🧭 Executive Summary

Telecom churn directly impacts recurring revenue and long-term customer value.
Using a combination of data enrichment, EDA-driven insights, and machine learning, this project builds a complete churn prevention strategy — the same approach used by companies like AT&T, Airtel, Verizon, and Jio.

🎯 Key Outcomes
Aspect	Result
Overall Churn	26.5%
High-Risk Segment Identified	Month-to-Month + Electronic Check + Tenure < 6 months
Model Accuracy (AUC)	0.837
Precision@Top10%	73% (Highly Targetable Group)
Revenue at Risk (CLV)	₹14.7M
Revenue Recovered (Targeting only Top 10%)	₹76,007
Net Gain after Campaign Cost	₹40,807
🧩 1. Business Problem

Churn is expensive because telecom revenue is recurring.
We define a SMART problem statement:

Reduce churn by 10–15% in the next 90 days among early-tenure, high-risk customers through targeted retention campaigns powered by data and machine learning.

🧩 2. Why Churn Happens (Business Lens)

Using enriched data + EDA, churn is strongly linked to:

⚠ High-risk predictors:

Contract Type — Month-to-Month
→ 42.7% churn (unstable customers)

Payment Method — Electronic Check
→ 45.3% churn (payment failures, lack of trust)

Tenure < 6 months
→ 52.9% churn (bad onboarding)

Low Engagement & High Support Tickets
→ Our synthetic features make this even more realistic
→ Mirrors actual telecom KPIs: NPS, CES, complaint counts

💡 3. Business Insights (Presented Like Consulting Slides)
📌 Insight 1 — Month-to-Month contract is the core churn driver
│ Contract Type         │ Churn Rate │
│-----------------------│------------│
│ Month-to-Month        │ 42.7%      │
│ One Year              │ 11.3%      │
│ Two Year              │ 2.8%       │


Why it matters:
These customers have high flexibility → high churn probability.
Retention must focus here first.

📌 Insight 2 — Switching payment method lowers churn by ~30%

Electronic Check → 45.3% churn
Auto-Pay (Bank Transfer) → 16.7% churn

Why it matters:
A simple operational change can drastically reduce churn.

📌 Insight 3 — First 6 months are the danger zone
Tenure 0–6 months → 52.9% churn
Tenure 49+ months → 9.5% churn


Why it matters:
Customer onboarding quality is one of the strongest drivers of loyalty.

📌 Insight 4 — High CLV customers are NOT the highest churners

Surprising insight:
High-revenue customers churn less → Better onboarding = more loyalty

This aligns with real-world telecom patterns.

🧩 4. Predictive Modeling (Machine Learning)
Model Used → Logistic Regression

Selected because:

Interpretable

Fast

Business-friendly
(business users can understand coefficients)

Performance Highlights
Metric	Score
AUC	0.837
Precision	0.643
Recall	0.531
F1 Score	0.582
🧭 5. Identifying High-Value Churn Risk Customers

We scored all customers and extracted the top 10% high-risk.

Metric	Value
Top customers flagged	704
Precision@Top10%	73%
CLV of these customers	₹506,713

These are the best targets for retention.

💰 6. Retention Strategy ROI (Executive Format)
Assumptions:

Cost per retention call = ₹50

Conversion rate = 15%

ROI Calculations
Item	Value
Campaign Cost	₹35,200
Recovered Revenue	₹76,007
Net Gain	₹40,807 ✔

Business Meaning:
→ Targeting only 10% of customers generates a 116% ROI
→ Operationally efficient & financially justified
