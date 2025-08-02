# 🧵 HandsMen Threads – Salesforce CRM Implementation

> **HandsMen Threads** is a premium fashion CRM platform designed during my **Salesforce internship** to streamline order management, customer engagement, and inventory tracking for a bespoke men's fashion brand.

---

## 📌 Project Overview

**HandsMen Threads** is built on Salesforce CRM to:
- Manage tailored clothing orders and customer details  
- Track inventory in real-time  
- Automate marketing and loyalty programs  
- Improve business efficiency with custom dashboards and flows

This project involved full-cycle CRM development including data modeling, automation, Apex programming, UI customization, and deployment.

---

## 🎯 Objectives

- ✅ Centralized customer, product, and inventory data
- ✅ Real-time stock & order tracking
- ✅ Loyalty program automation
- ✅ Email notifications and flow-based actions
- ✅ Role-based access & permissions

---

## 🧱 Data Model

| Object        | Description                             |
|---------------|-----------------------------------------|
| Customer      | Stores customer profiles and contact info |
| Order         | Tracks customer orders and status       |
| Product       | Catalog of available tailoring products |
| Inventory     | Stock details and levels                |
| Campaign      | Used for marketing and loyalty tracking |

🔗 Relationships: Lookup & Master-Detail  
🔐 Roles: CEO → Sales / Inventory / Marketing  
👤 Profile: Platform 1 with CRUD access

---

## 🛠️ Features Implemented

### ✅ CRM Functionality
- Custom Tabs: Customers, Orders, Products, Campaigns, Inventory  
- Dynamic Forms using Lightning App Builder  
- HTML Email Templates for notifications  
- Dashboards for stock & loyalty visualization

### ⚙️ Apex Logic
- `OrderTriggerHandler`: Validates order logic  
- `InventoryBatchJob`: Batch + scheduled Apex class for daily restocking  
- Validation Rules: Email format, order quantity, non-zero inventory  

### 🔁 Automation with Flows
- Order Confirmation Email  
- Loyalty Status Upgrade Flow  
- Stock Alert Flow (< 5 units)  

---

## 🧪 Testing & Quality

| Feature              | Scenario                        | Result |
|----------------------|----------------------------------|--------|
| Order Confirmation   | Triggered on confirmed order     | ✅ Email sent |
| Inventory Alert      | Stock < 5                        | ✅ Alert sent |
| Loyalty Flow         | Purchases > ₹1000                | ✅ Status updated |

- Test Class: `OrderTriggerHandlerTest.cls`  
- Manual tests via Data Loader & Form Submission  
- Debug Logs used for troubleshooting

---

## 🚀 Deployment

- ⚙️ Org Setup: 
- 🔁 Metadata Migration: Using Change Sets  
- 🔎 Post-deployment Smoke Testing  
- 🧩 Profiles, Roles, Sharing Rules configured  

---

## 🧠 Learning Outcome

- Salesforce Lightning Experience Development  
- Apex Trigger & Batch Job implementation  
- Real-world CRM workflow design  
- Hands-on with automation, validation, and data modeling  
- Experience with metadata deployment & maintenance  

---

## 📈 Future Enhancements

- 🔮 AI Chatbot for customer support  
- 📲 WhatsApp/SMS integration for order alerts  
- 📊 Predictive loyalty scoring via Einstein Analytics  

---

## 👨‍💻 Author

**Aditya Kumar Singh**  
🎓 DIT University, Dehradun  
📅 Project Date: July 2025  
🏢 Internship at Salesforce

---

## ⭐ Like This Project?

Give it a ⭐ on GitHub to show your support!

---
