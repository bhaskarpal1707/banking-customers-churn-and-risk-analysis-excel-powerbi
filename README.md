# 🏦 COMPREHENSIVE BANKING CUSTOMERS CHURN & RISK ANALYSIS

## 📌 Subtitle  
**Data-Driven Insights for Reducing Customer Churn and Managing Risk in the Banking Sector**
---

<img width="1540" height="863" alt="image" src="https://github.com/user-attachments/assets/dd48350b-7c44-49a4-baf4-3233cae4379d" />
<img width="1533" height="860" alt="image" src="https://github.com/user-attachments/assets/74786690-653e-4a05-9c20-1302f53ad6b8" />
<img width="1545" height="863" alt="image" src="https://github.com/user-attachments/assets/6ac5337c-1695-470d-bb86-f5c6c2598cf4" />

---

## 📑 Table of Contents
1. [Subtitle](#-subtitle)  
2. [Overview](#-overview)  
3. [Business Problems](#-business-problems)  
4. [Datasets](#-datasets)  
   - [Churn-Data](#1-churn-data)  
   - [Customers-Data](#2-customers-data)  
   - [Internet-Data](#3-internet-data)  
5. [Tools & Technologies](#-tools--technologies)  
6. [Project Workflow](#-project-workflow)  
7. [Key Insights](#-key-insights)  
8. [Final Recommendations](#-final-recommendations)  
9. [Author & Contact](#-author--contact)  
10. [Tags & Keywords](#-tags--keywords)  

---

## 📖 Overview  
Customer churn is one of the most critical challenges in the banking and financial industry. High churn directly impacts revenue, profitability, and long-term growth. This project leverages **Power BI** to analyze customer churn and risk factors, uncover hidden patterns, and provide actionable recommendations for customer retention.  

The analysis is based on three structured datasets and combines **descriptive analytics** with **data visualization techniques** to deliver a comprehensive view of churn behavior across multiple dimensions such as **tenure, contract type, payment method, internet service, and billing preferences**.  

---

## 💡 Business Problems  
- High churn in **early-tenure customers** causing revenue leakage.  
- **Month-to-month contracts** driving instability compared to long-term agreements.  
- **Electronic check payment method** strongly associated with high churn.  
- Dissatisfaction among **fiber internet users** leading to higher exit rates.  
- Lack of **onboarding, device protection, and customer support** contributing to early attrition.  

---

## 📊 Datasets  

The project uses **three datasets** that collectively provide customer demographics, service usage, and churn outcomes.  

### 1. **Churn-Data**  
This dataset contains the **target variable (Churn)** along with customer-level financial and contractual details.  
Key fields include:  
- **CustomerID** → Unique identifier for each customer.  
- **Tenure** → Duration of the customer’s relationship with the company.  
- **Contract** → Type of contract (Month-to-month, One-year, Two-year).  
- **PaperlessBilling** → Indicates if the customer uses paperless billing.  
- **PaymentMethod** → Method of payment (Electronic check, Bank transfer, Credit card, Mailed check).  
- **MonthlyCharges** → Monthly bill amount paid by the customer.  
- **TotalCharges** → Lifetime value spent by the customer.  
- **Churn** → Target variable showing whether the customer left (Yes/No).  

### 2. **Customers-Data**  
This dataset provides demographic and household-level attributes of customers.  
Key fields include:  
- **Gender** → Male/Female.  
- **SeniorCitizen** → Whether the customer is a senior citizen (1/0).  
- **Partner** → If the customer has a partner.  
- **Dependents** → If the customer has dependents (children/parents).  
- **PhoneService** → If the customer subscribed to phone service.  
- **MultipleLines** → Whether multiple lines were used.  

### 3. **Internet-Data**  
This dataset covers internet service preferences and add-on services.  
Key fields include:  
- **InternetService** → Type of service (DSL, Fiber optic, None).  
- **OnlineSecurity** → Whether the customer subscribed to online security.  
- **OnlineBackup** → Availability of online backup service.  
- **DeviceProtection** → Device protection subscription.  
- **TechSupport** → Technical support availability.  
- **StreamingTV** → Access to streaming TV.  
- **StreamingMovies** → Access to streaming movies.  

Together, these datasets allow for a **360° analysis of churn behavior**, covering demographics, contract terms, internet usage, and payment behavior.  

---

## 🛠 Tools & Technologies  
- **Excel** → Data understanding and preliminary cleaning.  
- **Power BI** → Dashboard creation, visualization, and storytelling.  
- **DAX (Data Analysis Expressions)** → Calculations and custom measures.  
- **Power Query** → Data transformation and modeling.  



## 🔄 Project Workflow  
1. **Excel**  
   - Initial dataset exploration.  
   - Basic cleaning, formatting, and validation.  

2. **Power BI**  
   - Data loading and transformation using **Power Query**.  
   - Creation of measures and KPIs with **DAX**.  
   - Building interactive dashboards for **Customer Churn & Risk Analysis**.  
   - Storytelling through categorical and numerical dashboards.  

---

## 📌 Key Insights  

The dashboards revealed important patterns and churn drivers:  

### 1. **Tenure & Customer Lifecycle**  
- Majority of churn happens in the **first year** of tenure.  
- As tenure increases, churn rate significantly drops—**long-tenure customers are more loyal**.  
- Short-tenure groups (0–12 months) show **mixed churn and non-churn profiles**, signaling a **need for strong onboarding**.  

### 2. **Monthly Charges & Billing**  
- **Churners usually pay higher monthly charges** compared to non-churners.  
- New customers paying higher bills are more sensitive to price, leading to quick exits.  
- Bills stabilize over long tenure, lowering churn.  

### 3. **Contracts & Customer Retention**  
- **Month-to-month contracts have the highest churn (~46%)**.  
- Customers on **one- or two-year contracts churn far less**.  
- Upgrading customers from flexible to fixed-term contracts is a strong retention lever.  

### 4. **Payment Methods**  
- **Electronic check users** form the largest churn segment.  
- **Auto-pay methods** like bank transfer or credit card are associated with **lower churn**.  
- Encouraging auto-pay adoption reduces churn risk significantly.  

### 5. **Internet Services & Add-Ons**  
- **Fiber-optic users churn more than DSL users**, indicating dissatisfaction with service quality or high expectations.  
- Customers with **device protection, online security, and tech support** churn less.  
- Lack of support and add-ons increases churn vulnerability.  

### 6. **Value-Added Services (Streaming, Paperless Billing)**  
- Customers with **streaming services** churn depending on quality and network stability.  
- **Paperless billing customers churn more** in certain segments due to unclear billing.  
- Billing transparency and reminders can improve retention.  

### 7. **Demographics**  
- Churn is fairly **even across genders**.  
- Retention efforts should focus on **behavioral and contractual factors**, not demographics.  

### 8. **Overall Takeaways**  
- **Top churn drivers**: Month-to-month contracts, electronic check payments, and fiber internet dissatisfaction.  
- **Quick wins**: Promote auto-pay, incentivize contract upgrades, and enhance onboarding + service quality for fiber customers.  

## ✅ Final Recommendations  

1. **Early-Onboarding Programs**  
   - Focus retention efforts in the **first year of tenure**.  
   - Offer **welcome discounts, loyalty perks, or personalized plans** for new customers.  

2. **Contract Upgrades**  
   - Encourage month-to-month customers to switch to **1–2 year contracts** with incentives.  

3. **Payment Optimization**  
   - Promote **auto-pay options (bank transfer/credit card)** to reduce friction and prevent churn.  

4. **Service Quality Improvements**  
   - Enhance **fiber internet service reliability** and proactively communicate during outages.  
   - Expand **technical support availability (24/7, omnichannel)**.  

5. **Cross-Selling Value Additions**  
   - Upsell **device protection plans** and **streaming bundles** to increase stickiness.  

6. **Transparent Billing Practices**  
   - Simplify **paperless billing** with reminders and bill clarity to prevent disputes.  

---

## 👤 Author & Contact  

**Bhaskar Pal**  
*Aspiring Data Analyst*  

📧 Email: [bhaskarpal.official@gmail.com](mailto:bhaskarpal.official@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/bhaskar-pal-2k02](https://www.linkedin.com/in/bhaskar-pal-2k02/)  
🔗 Portfolio: [bhaskarpal1707.github.io/portfolio](https://bhaskarpal1707.github.io/portfolio/)  

---

## 📌 Tags & Keywords  
`#DataAnalytics` `#PowerBI` `#CustomerChurn` `#BankingAnalytics` `#DataVisualization` `#BusinessInsights` `#DAX` `#PowerQuery` `#Dashboard`  
