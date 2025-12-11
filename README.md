# 📊 Customer Churn Strategy & Retention Optimization  
**End-to-End Analytics | Feature Engineering | Predictive Modeling | Revenue Impact | Tableau Storyboard**

---

## 🧭 Executive Summary

Telecom churn directly impacts recurring revenue and long-term customer value.  
This project builds a **complete, business-focused churn prevention solution** using:

- Real + synthetic hybrid dataset  
- Extensive EDA  
- Feature engineering (CLV, Engagement Score, Tickets Opened)  
- Machine Learning (Churn Prediction)  
- Revenue impact modeling  
- Tableau dashboard for executive insights  

---

## 🎯 Key Outcomes

| Metric / Result | Value |
|-----------------|--------|
| **Overall Churn Rate** | **26.5%** |
| **High-Risk Segment** | Month-to-month, Electronic Check, Tenure < 6 months |
| **Model AUC** | **0.837** |
| **Precision@Top10% (High-Risk Customers)** | **73%** |
| **Revenue at Risk (CLV)** | **₹14.7M** |
| **Recovered Revenue (Using Targeted Campaign)** | **₹76,007** |
| **Net Gain After Costs** | **₹40,807** |

---

## 🧩 1. Business Problem

**SMART Problem Statement:**  
Reduce telecom customer churn by **10–15% within 90 days** by identifying high-risk users and applying targeted retention strategies.

---

## 🧩 2. Why Customers Churn (Business Lens)

### **Top Churn Drivers Identified:**

#### 🔹 Contract Type  
- Month-to-month → 42.7% churn
- One-year → 11.3%
- Two-year → 2.8%


#### 🔹 Payment Method  
- Electronic Check → 45.3% churn
- Auto-Pay (Bank Transfer) → 16.7%


#### 🔹 Tenure  
- Tenure 0–6 months → 52.9% churn
- Tenure 49+ months → 9.5%


#### 🔹 Customer Engagement  
- Low engagement score + high support tickets correlate heavily with churn.

---

## 🧩 3. Business Insights (Consulting Style)

### Insight 1 — Month-to-Month Customers Drive Churn  
- They make up the **largest risk group**  
- Lack long-term commitment  
- Prime candidates for discount/contract campaigns  

---

### Insight 2 — Payment Method Predicts Loyalty  
- Electronic check users churn **3× more**  
- Auto-payment users show significantly higher retention  
- Improving payment onboarding reduces churn

---

### Insight 3 — First 6 Months Are Critical  
- Over **52% churn** happens early  
- Poor onboarding = customer drop-off  
- Companies should focus on welcome journeys, support quality, and proactive outreach

---

### Insight 4 — High CLV Customers Churn Less  
- Indicates satisfaction and good onboarding  
- Low CLV + high churn flags “unhappy new users”

---

## 🧩 4. Predictive Modeling

Model: **Logistic Regression**  
Chosen due to interpretability + business friendliness.

### Model Performance

| Metric | Score |
|--------|--------|
| **AUC** | **0.837** |
| Precision | 0.643 |
| Recall | 0.531 |
| F1 Score | 0.582 |

Good separation between churners and non-churners.

---

## 🧭 5. High-Value Churn Risk Identification

Using predicted churn probabilities:

| Metric | Value |
|--------|--------|
| Customers in Top 10% High Risk | **704** |
| Precision@Top10% | **73%** |
| CLV of High-Risk Group | **₹506,713** |

These users are the **most cost-effective targets** for retention.

---

## 💰 6. Retention Strategy ROI

### Assumptions:
- Cost per customer contact = ₹50  
- Conversion rate = 15%  

### Results:
| Item | Amount |
|-------|---------|
| Campaign Cost | ₹35,200 |
| Revenue Recovered | ₹76,007 |
| **Net Gain** | **₹40,807** |

➡ **116% ROI** — highly profitable retention strategy.

---

## 📊 7. Tableau Dashboard

Dashboard contains:

### **Page 1 — Executive Overview**
- Total customers  
- Churn rate  
- Revenue at risk (CLV)  
- High-risk customer distribution  

### **Page 2 — Churn Drivers**
- Churn by contract type  
- Churn by tenure bucket  
- Churn by payment method  
- Engagement vs Support Tickets  

### **Page 3 — ML Segmentation**
- Predicted churn score  
- High-risk clusters  
- Revenue impact simulation  

### **Page 4 — Retention Strategy**
- Recommended actions  
- Estimated ROI  
- Top segments to target  

---

## 🏆 What This Project Demonstrates

✔ End-to-end analyst workflow  
✔ Strong data cleaning + feature engineering  
✔ Ability to derive business insights  
✔ ML modelling + evaluation  
✔ Revenue modeling & strategic impact  
✔ Executive-level dashboard storytelling  
✔ A real, business-ready churn reduction plan


---


## 👨‍💻 Tools Used

- Python (Pandas, NumPy, Scikit-learn)
- SQL (for business logic)
- Tableau
- Excel
- Matplotlib / Seaborn

---
