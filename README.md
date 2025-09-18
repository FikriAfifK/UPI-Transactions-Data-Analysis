# 📊 UPI Transactions Data Analysis

UPI transaction analysis using an interactive dashboard. 
This project visualizes transaction data based on city, bank, merchant, 
and user demographics to find useful patterns and insights.

---

## 🚀 Dashboard Page

### 🟢 Page 1 – Transaction Overview
![Transactions Dashboard](/page1.png)
- Displays transaction summaries based on:
  - BankNameSent & BankNameReceived
  - City
  - DeviceType
  - Gender
  - Age Groups
  - MerchantName
  - PaymentMethod
  - Purpose
  - TransactionType

#### 🔎 Key Features
- Distribution of transactions by category.
- Summary of transaction volume.
- General trends in UPI transactions.

---

### 🟠 Page 2 – Transaction Analysis by City & Currency
![Transactions Dashboard](/page2.png)
Focus on monthly analysis by city with different currencies.

#### 🔎 Filter Features
- Bank Name Sent / Received
- City
- Device Type
- Gender & Age Groups
- Merchant Name
- Payment Method
- Purpose & Transaction Type

#### 📑 Analysis Table
- **City**: 
  - Bangalore → EUR
  - Delhi → USD
  - Hyderabad → GBP
  - Mumbai → INR
- Columns:
  - **Amount** → number of transactions per month.
  - **Remaining Balance** → remaining balance after transactions.
- Color highlights → mark significant values.

#### 🎯 Insight
- Comparison of monthly transactions between cities.
- Monthly spending patterns & remaining balances.
- Trends in transaction growth or decline.
- Identification of cities with:
  - Highest transaction volume.
  - Largest remaining balance.

---

## 🛠️ Tech Stack
- **Power BI** → for data visualization  
- **Power Query** → for data transformation  
- **DAX** → for aggregate value & ratio calculations  
