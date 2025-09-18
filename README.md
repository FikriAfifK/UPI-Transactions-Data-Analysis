# 📊 UPI Transactions Data Analysis

Interactive analysis of UPI (Unified Payments Interface) transactions using dashboards. UPI is a real-time payment system developed by the **National Payments Corporation of India (NPCI)**, enabling instant bank-to-bank transfers using **Virtual Payment Address (VPA)**, mobile number, or QR Code. Popular UPI-based apps in India include Google Pay, PhonePe, Paytm, and BHIM.

---

## 🚀 Features
- Interactive dashboard for UPI transaction analysis.
- Dynamic filters (Bank, City, Gender, Device Type, Payment Method, etc.).
- Visualizations in both **charts** and **matrix tables**.
- Insights by month, city, currency, and merchant.

---

## 📑 Dashboard Pages

### 🔹 Page 1 – Transactions & Balance Chart
![Transactions Dashboard](/page1.png)
- Displays **Line** and **Column** charts for:
  - Transaction Amount
  - Remaining Balance
- **Bookmark toggle** to switch between line and column charts.
- **Available filters**: BankNameSent, BankNameReceived, City, DeviceType, Gender, Age Groups, MerchantName, PaymentMethod, Purpose, TransactionType.

### 🔹 Page 2 – Matrix Table
![Transactions Dashboard](/page2.png)
- Displays data in a matrix format with:
  - **Rows** : Month
  - **Columns** : City, Currency
  - **Values** : Amount, Remaining Balance
- Uses the same filters as Page 1.
- Enables cross-city and cross-currency analysis with monthly breakdowns.

---

## 🛠️ Tech Stack
- **Power BI** → for data visualization  
- **Power Query** → for data transformation  
- **DAX** → for aggregate value & ratio calculations

---

## 🎯 Insights
- Monthly distribution of UPI transactions in 2024.
- Comparison of transactions & remaining balances across major cities (Mumbai, Delhi, Bangalore, Hyderabad).
- Usage trends by merchant, payment method, and device type.
