# Account Payable Aging Analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Objective](#objective)
4. [Tools Used](#tools-used)
5. [Process](#process)
6. [Key Insights](#key-insights)
7. [Recommendations](#recommendations)
8. [Live Dashboard](#link-to-live-dashboard)
9. [Connect With Me](#connect-with-me)

---

# Project Overview

The Accounts Payable Aging Analytics Dashboard was developed to provide management with a clear view of Perfect Marine's outstanding supplier obligations, overdue payments, vendor exposure, and overall financial health.

The dashboard enables stakeholders to monitor Accounts Payable performance, identify payment risks, assess cash flow pressures, and make informed decisions regarding vendor payments and working capital management.

By analyzing aging buckets, overdue balances, vendor liabilities, and invoice volumes, the dashboard supports proactive financial planning and risk mitigation.


<img width="1337" height="794" alt="Screenshot 2026-06-04 174704" src="https://github.com/user-attachments/assets/7c8ccd64-bb7d-4062-87f7-dd1e5aac320d" />

---

# Business Problem

Perfect Marine requires visibility into its Accounts Payable position to answer critical business questions:

* How much does the company currently owe suppliers?
* What proportion of outstanding payables is overdue?
* Which vendors pose the greatest financial exposure?
* How are liabilities distributed across aging categories?
* Where are potential cash flow risks concentrated?
* How can management prioritize payments to reduce financial risk?

Without a centralized reporting solution, delayed payments can lead to:

* Supplier relationship deterioration
* Operational disruptions
* Increased liquidity pressure
* Late payment penalties
* Poor working capital management


<img width="1338" height="775" alt="Screenshot 2026-06-04 174734" src="https://github.com/user-attachments/assets/3342fae1-8f9a-46a6-850a-7ccf4ce03926" />

---

# Project Objectives

The primary objectives of this dashboard are to:

### Financial Visibility

Provide a comprehensive view of outstanding Accounts Payable obligations.

### Overdue Monitoring

Identify overdue invoices and quantify overdue exposure.

### Vendor Risk Assessment

Analyze payable balances across vendors to identify concentration risks.

### Aging Analysis

Track liabilities across aging buckets to determine payment urgency.

### Cash Flow Planning

Support treasury and finance teams in managing cash requirements effectively.

### Decision Support

Enable management to prioritize vendor payments and reduce financial risk.

<img width="1349" height="788" alt="Screenshot 2026-06-04 174759" src="https://github.com/user-attachments/assets/ff760c7f-f489-4181-a8d1-42a6df621561" />


---

# Tools Used

| Tool                            | Purpose                                              |
| ------------------------------- | ---------------------------------------------------- |
| Microsoft Power BI              | Dashboard Development & Data Visualization           |
| Power Query                     | Data Transformation & Cleaning                       |
| DAX (Data Analysis Expressions) | KPI Calculations and Measures                        |
| Excel / ERP Data Source         | Accounts Payable Transaction Data                    |
| Data Modeling                   | Relationship Management and Performance Optimization |

---

# Project Process

## 1. Data Collection

Accounts Payable transactional data was gathered from internal financial systems, including:

* Vendor details
* Invoice records
* Payment status
* Due dates
* Invoice amounts

---

## 2. Data Cleaning and Transformation

The dataset was prepared by:

* Removing duplicates
* Handling missing values
* Standardizing date formats
* Validating invoice amounts
* Creating aging classifications

---

## 3. Data Modeling

Relationships were established between:

* Vendors
* Invoices
* Aging Buckets
* Cash Flow Categories

This enabled dynamic filtering and drill-down analysis.

---

## 4. KPI Development

Key metrics were created to monitor AP performance:

* Total Amount
* Total AP
* Overdue AP
* Overdue Percentage
* Number of Vendors
* Number of Invoices

---

## 5. Dashboard Design

Interactive dashboards were developed to allow users to:

* Filter by Vendor
* Filter by Aging Bucket
* Filter by Cash Flow Bucket
* Analyze payment trends
* Assess financial risk exposure


---

# Key Insights

## 1. Significant Overdue Exposure

Out of the total Accounts Payable balance of **₦635.57M**, approximately **₦412.35M** is overdue.

This represents:

**64.88% of total AP**

### Implication

The company faces elevated short-term liquidity risk and may experience increased pressure from suppliers.

---

## 2. Most Overdue Balances Are Recently Due

The largest overdue category is:

| Aging Bucket | Amount   |
| ------------ | -------- |
| 1–30 Days    | ₦216.19M |

representing:

**34.01% of Total AP**

### Implication

Most overdue invoices are still in an early delinquency stage and can be addressed before becoming severe collection issues.

---

## 3. Limited Long-Term Delinquency

Only:

**₦18.78M**

is aged between:

**61–90 Days**

representing:

**2.95% of Total AP**

### Implication

The company has not yet accumulated substantial long-term overdue obligations.

---

## 4. Healthy Portion of Current Liabilities

A total of:

**₦223.21M**

remains within payment terms.

This represents:

**35.12% of Total AP**

### Implication

There is still flexibility in payment scheduling and cash management.

---

## 5. Vendor Concentration Risk Exists

The dashboard indicates that the majority of AP balances are concentrated among a small number of vendors, including:

* Vertex Oilfield Services
* Titan Procurement Ltd
* Alpha Supplies Ltd
* CrestTech Nigeria

### Implication

Supplier dependency increases operational and financial risk if payment delays persist.

---

## 6. High Invoice Volume Requires Monitoring

The company manages:

**220 outstanding invoices**

across:

**8 vendors**

### Implication

Manual tracking may become inefficient, increasing the risk of missed payment deadlines.


<img width="1828" height="809" alt="Screenshot 2026-06-04 174824" src="https://github.com/user-attachments/assets/8cf8d3fe-6fe8-4377-92e4-686da89b2931" />

---

# Recommendations

## 1. Prioritize Overdue Payments

Focus on settling invoices within the:

* 1–30 day bucket
* 31–60 day bucket

to prevent migration into older aging categories.

### Expected Benefit

Reduction in overdue exposure and improved supplier confidence.

---

## 2. Implement Vendor Payment Prioritization

Classify suppliers into payment tiers based on:

* Operational importance
* Invoice value
* Business impact

### Expected Benefit

More efficient allocation of limited cash resources.

---

## 3. Negotiate Extended Payment Terms

Engage major vendors to discuss:

* Payment extensions
* Installment arrangements
* Revised credit terms

### Expected Benefit

Improved short-term liquidity.

---

## 4. Strengthen Cash Flow Forecasting

Integrate Accounts Payable planning into:

* Treasury forecasting
* Procurement planning
* Budget management

### Expected Benefit

Reduced future overdue balances.

---

## 5. Introduce Automated AP Monitoring

Deploy alerts for:

* Upcoming due dates
* Overdue invoices
* High-risk vendors

### Expected Benefit

Improved payment discipline and reduced manual oversight.

---

## 6. Monitor Vendor Concentration Risk

Track supplier exposure regularly and diversify procurement where possible.

### Expected Benefit

Reduced dependency on a small number of vendors.

---

# Business Impact

The dashboard provides management with a single source of truth for monitoring Accounts Payable performance and financial obligations. By identifying overdue balances, aging risks, and vendor concentration issues, stakeholders can take proactive action to improve liquidity, strengthen supplier relationships, and optimize working capital management.

---

# Conclusion

The analysis reveals that Perfect Marine currently carries **₦635.57M** in Accounts Payable obligations, with **64.88% (₦412.35M)** already overdue. While the majority of overdue balances remain within the early aging stages, prompt action is required to prevent escalation into long-term delinquency. Through improved payment prioritization, vendor management, cash flow forecasting, and AP monitoring, the organization can significantly reduce financial risk and enhance operational stability.

# Live dashboard
[View My Live Dashboard](https://app.powerbi.com/groups/me/reports/b422dcb0-f97a-4c3c-8f0c-0d5e7e2e3af9/28d70c090ca0d6d5d4ba?experience=power-bi)

# Connect with Me
(www.linkedin.com/in/chukwuebuka-ugwu-01a052194)
