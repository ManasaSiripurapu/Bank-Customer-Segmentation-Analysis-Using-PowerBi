# 🏦 Bank Customer Segmentation Analysis Using Power BI

## 📌 Problem Statement
Banks manage massive volumes of customer and transaction data, but without proper segmentation, it becomes difficult to identify high-value customers, understand transaction behavior, and design targeted strategies.  

This project aims to analyze bank customer demographics, transaction patterns, and customer segments using **Power BI**, enabling data-driven decisions to improve customer loyalty, acquisition, and retention.

---

## 📊 Dataset Overview
- **Source**: Bank transaction dataset  
- **Records before cleaning**: 1,048,568  
- **Records after cleaning**: 1,045,170  

---

## 📁 Fields Used
- TransactionID  
- CustomerID  
- CustomerDOB  
- CustGender  
- CustLocation  
- CustAccountBalance  
- TransactionDate  
- TransactionTime  
- TransactionAmount  

---

## 🧹 Data Cleaning & Preparation
The dataset was cleaned and transformed using **Power BI Power Query**:

- Converted **CustomerDOB**, **TransactionDate**, and **TransactionTime** to correct data types  
- Replaced null or missing gender and location values with **"Unknown"**  
- Removed invalid records and errors  
- Ensured consistency in date, time, and numeric formats  

---

## 🧮 Calculated Columns (DAX)
- **Customer Age**  
- **Age Group** (18–24, 25–34, 35–44, 45–54, 55+)  
- **State** (derived from customer location)  

---

## 📐 Measures Created (DAX)
- Total Customers  
- Total Transactions  
- Total Revenue  
- Average Transaction Amount  
- Loyal Customers  
- Regular Customers  
- New Customers  
- Lost Customers  
- Transaction Frequency  
- Average Account Balance  

---

## 📈 Key Insights (Business-Relevant)
- The bank has **~8.8 lakh customers** and **1.05+ million transactions**, showing strong operational scale.  
- **Male customers dominate (~71%)**, indicating a gender-skewed customer base.  
- The **35–44 age group** is the largest and most valuable segment.  
- **Maharashtra** has the highest customer concentration, making it a key revenue market.  
- Most transactions occur **after 12 PM**, with a **peak at 7 PM**, generating **₹14.8 crores**.  
- **Regular customers (~0.66 million)** form the majority, while **loyal customers are extremely low (~50)**.  
- **Lost customers significantly outnumber new customers**, signaling retention challenges.  
- States like **Assam and Bihar** show very low customer penetration.  

---

## 💡 Recommendations to the Bank

### 🔁 Convert Regular Customers to Loyal
- Launch **personalized reward programs** for the 35–44 age group  
- Offer **location-specific benefits** in Maharashtra (cashbacks, premium services)  
- Introduce **transaction-based loyalty points** during peak hours (post-12 PM)  

### 🌱 Increase New Customers
- Run **digital acquisition campaigns** targeting younger age groups (18–34)  
- Provide **referral bonuses** and simplified account onboarding  
- Promote **first-transaction rewards** to encourage early engagement  

### 🚫 Reduce Lost Customers
- Identify low-activity users and trigger **re-engagement offers**  
- Use **behavior-based alerts** (declining transactions, low balances)  
- Improve **customer support responsiveness** and issue resolution  

### 🌍 Grow Presence in Low-Penetration States (Assam & Bihar)
- Launch **regional campaigns** with local language support  
- Partner with **local businesses and institutions**  
- Offer **basic, low-balance accounts** tailored to regional needs  

---

## 🛠 Tools Used
- Power BI  
- DAX  
- Power Query  
- Data Modeling & Visualization  

---

## 📌 Conclusion
This project demonstrates how **customer segmentation and transaction analysis** can uncover growth opportunities, improve retention, and drive strategic decision-making in the banking domain through effective data storytelling.
