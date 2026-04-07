# Credit_Card_Analysis_Dashboard
Power Bi Dashboard
<img width="1110" height="621" alt="Screenshot credit card transaction report" src="https://github.com/user-attachments/assets/72ddc07d-b4a1-4c1e-b631-e552ead96932" />

<img width="1113" height="617" alt="Screenshot credit card customer report" src="https://github.com/user-attachments/assets/8d94e9f4-9d44-4960-8d57-6fe4aa091493" />
# 💳 Credit Card Data Analysis — Power BI Dashboard Project

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Banking%20%26%20Finance-navy?style=for-the-badge)

---

## 📌 Project Overview

This is a **real-world end-to-end Power BI project** built on credit card data from a US-based financial company covering the **full year 2023 (Week 1 to Week 53)**.

The project has **two dashboards that work together** — one focuses on the **customers** (who they are and how much they earn for the business), and the other focuses on the **transactions** (how they spend, which card they use, and which quarter performs best). Together, they give senior management a **complete 360-degree view** of the credit card business.

The aim is simple — **turn raw data into clear answers** so that business leaders can make faster and smarter decisions without looking at a single spreadsheet.

---

## 🎯 Problem Statement

Credit card companies collect millions of rows of data every week — customer details, spending habits, transaction methods, interest earned, and more. But raw data alone does not help anyone make decisions.

**The challenge:** How do we take all this data and show it in a way that is simple, visual, and immediately useful to senior managers?

**The solution:** Two connected Power BI dashboards — one for customer insights, one for transaction insights — that tell the full story of the business in under 2 minutes.

---

## 📊 Dashboard 1 — Credit Card Customer Report

> *"Who are our customers and how much value do they bring to the business?"*

This dashboard answers everything about **customer demographics and revenue performance**.

### 🔢 Key Numbers (KPI Cards)

| Metric | Value |
|--------|-------|
| Total Revenue | **57 Million** |
| Total Income | **588 Million** |
| Total Interest Earned | **8 Million** |
| Customer Satisfaction Score (CSS) | **3.19 / 5** |

### 📈 Visuals & What They Tell Us

**Revenue by Week (Line Chart)**
Shows how revenue moved every single week from January 2023 to December 2023. Revenue stayed consistently between **0.4M and 0.8M** throughout the year — which means the business is stable and has no dangerous drops.

**Revenue by Customer Job Type (Table)**

| Job Group | Total Revenue | Total Income | Total Interest Earned |
|-----------|--------------|--------------|----------------------|
| Blue-collar | 7.0M | 73.5M | 9.67M |
| Businessman | 17.6M | 190.3M | 25.84M |
| Govt | 8.3M | 90.8M | 11.82M |
| Retirees | 4.6M | 49.6M | 6.41M |
| Self-employed | 8.5M | 77.6M | 11.41M |
| White-collar | 10.2M | 105.6M | 14.64M |
| **Total** | **56.5M** | **587.5M** | **79.82M** |

**Top 5 City (Pie Chart)**
Our customers are spread across 5 major US cities with a very balanced distribution — City 1: 24.45%, City 2: 24.37%, City 3: 24.23%, City 4: 18.73%, City 5: 8.23%. No single city dominates, which means the business is geographically diversified and not dependent on one region.

**Age Group (Bar Chart)**
The 40–50 age group is our biggest customer segment at **14M**, followed by 50–60 at **10M** and 30–40 at **6M**. Younger (20–30) and older (60+) customers are a very small part of the business.

**Income Group (Bar Chart)**
High Income customers lead at **30M**, followed by Medium Income at **16M** and Low Income at **11M**. This tells us our best customers are financially stable and have strong spending power.

**Education Group (Bar Chart)**
Graduates are the largest group at **23M**, followed by High School at **11M**. Post-graduates and Doctorate holders are a small but premium segment.

**Marital Group (Bar Chart)**
Married customers (29M) slightly outnumber Single customers (24M). A small group of 4M has unknown marital status.

**Gender Filter (Slicer)**
All visuals can be filtered between Male (M) and Female (F) customers to compare behavior across genders.

**Week Start Date Filter (Slicer)**
All visuals can be filtered to any specific week of the year for granular weekly reporting.

---

## 📊 Dashboard 2 — Credit Card Transaction Report

> *"How are customers spending, which card type performs best, and which quarter was strongest?"*

This dashboard answers everything about **spending patterns, transaction methods, and quarterly performance**.

### 🔢 Key Numbers (KPI Cards)

| Metric | Value |
|--------|-------|
| Total Revenue | **57 Million** |
| Total Interest Earned | **8 Million** |
| Total Transaction Amount | **46 Million** |
| Total Transaction Count | **667 Thousand** |

### 📈 Visuals & What They Tell Us

**QTR Revenue & Total Transaction Count (Combo Chart)**
Shows quarterly revenue (bars) alongside transaction volume (line) side by side.

| Quarter | Revenue | Transaction Count |
|---------|---------|------------------|
| Q1 | 14.0M | 163.3K |
| Q2 | 13.8M | 164.2K |
| Q3 | 14.2M | 166.6K |
| Q4 | 14.5M | 173.2K |

Revenue grew steadily from Q1 to Q4 — **Q4 is the strongest quarter** with 14.5M in revenue and 173.2K transactions.

**Revenue by Card Category (Table + Bar Chart)**

| Card Type | Total Revenue | Total Transaction Amount | Total Interest Earned |
|-----------|--------------|--------------------------|----------------------|
| Blue | 47.1M | 37.8M | 66.14M |
| Gold | 2.5M | 2.0M | 3.84M |
| Platinum | 1.1M | 0.9M | 1.61M |
| Silver | 5.6M | 4.6M | 8.21M |

**Blue card is the clear winner** — it generates 47M out of the total 57M revenue. This means the entry-level card holds the highest business value.

**Revenue by Transaction Method (Bar Chart)**
- Swipe: **36M** — most customers still prefer to physically swipe their card
- Chip: **17M** — chip-based payments are second
- Online: **4M** — online transactions are the lowest but growing

**Total Interest Earned by Car Owner (Pie Chart)**
- Non-car owners: **59.27%** of total interest
- Car owners: **40.73%** of total interest

Customers who do not own a car use credit cards more heavily for everyday expenses — which means they generate more interest income for the business.

**Revenue by Expense Type (Bar Chart)**
- Bills: **14M** (highest — customers use credit cards mostly for bill payments)
- Entertainment: **10M**
- Fuel: **10M**
- Grocery: **9M**
- Food: **8M**
- Travel: **6M**

**Revenue by Education Level (Bar Chart)**
Graduate customers lead at 23M — consistent with Dashboard 1, confirming educated customers are our most active users.

**Revenue by Job Type (Bar Chart)**
Businessman at 18M leads, followed by White-collar at 10M — again consistent with Dashboard 1, confirming data reliability across both reports.

**Quarter & Gender Filters (Slicers)**
All visuals can be filtered by Q1/Q2/Q3/Q4 and by Male/Female for detailed drill-down analysis.

---

## 🔗 How Both Dashboards Are Connected

These two dashboards are not separate reports — they are **two sides of the same story**:

| Dashboard 1 — Customer Report | Dashboard 2 — Transaction Report |
|-------------------------------|----------------------------------|
| Tells us WHO our customers are | Tells us HOW they spend |
| Shows revenue by job, age, income | Shows revenue by card type, expense category |
| Covers weekly performance | Covers quarterly performance |
| Focuses on customer demographics | Focuses on transaction behavior |
| **Together they give a complete business picture** | ✅ |

Both dashboards share the same total revenue (57M) and total interest (8M) KPIs — proving the data is fully synced and consistent.

---

## 🔑 Top 10 Business Insights

1. **Businessmen are the #1 revenue segment** — generating 17.6M in Dashboard 1 and 18M in Dashboard 2. Any targeted marketing should prioritize this group.
2. **Blue card holders generate 83% of total revenue** (47M out of 57M) — the most common card is also the most valuable.
3. **Q4 is the strongest quarter** with 14.5M revenue and 173.2K transactions — holiday season drives spending.
4. **Swipe transactions dominate** at 36M — physical card usage is still preferred over online.
5. **Customers aged 40–50 are the most valuable age group** at 14M — marketing should target this segment.
6. **High-income customers contribute 30M** — over half the total revenue comes from the premium income segment.
7. **Graduate customers are the most active** at 23M in both dashboards — education level is a strong predictor of card usage.
8. **Bills and Entertainment are the top spending categories** together accounting for 24M — customers rely on credit cards for regular monthly expenses.
9. **Revenue was consistent across all 53 weeks of 2023** — the business has a stable, loyal customer base with no dangerous seasonal drops.
10. **Non-car owners generate 59.27% of interest income** — they depend more on credit for daily expenses, making them highly profitable customers.

---

## 🛠️ Tools & Technologies Used

| Tool | How It Was Used |
|------|----------------|
| **Microsoft Power BI Desktop** | Building both dashboards, creating visuals, adding slicers |
| **Power Query (M Language)** | Cleaning raw data — removing nulls, fixing data types, merging tables |
| **DAX (Data Analysis Expressions)** | Writing custom measures for Revenue, Interest, Transaction Count, CSS |
| **Excel / CSV** | Source data files used as input |
| **Bing Maps (Power BI built-in)** | Geographic map visual showing customer locations across the US |

---

## 📐 DAX Measures Written

```dax
-- Total Revenue
Total Revenue = SUM(credit_card[Revenue])

-- Total Interest Earned
Total Interest = SUM(credit_card[interest_earned])

-- Total Transaction Amount
Total Trans Amt = SUM(credit_card[Total_Trans_Amt])

-- Total Transaction Count
Total Trans Count = COUNT(credit_card[Client_Num])

-- Customer Satisfaction Score
CSS = AVERAGE(credit_card[Customer_Sat_Overall])

-- Revenue by Gender (used in slicer)
Male Revenue = CALCULATE([Total Revenue], customer[Gender] = "M")
Female Revenue = CALCULATE([Total Revenue], customer[Gender] = "F")

-- Week-over-Week Revenue Change
WoW Revenue Change % =
    DIVIDE(
        [Total Revenue] - CALCULATE([Total Revenue], DATEADD(Dates[Date], -7, DAY)),
        CALCULATE([Total Revenue], DATEADD(Dates[Date], -7, DAY))
    )
```

---

## 📁 Project Structure

```
📦 Credit-Card-PowerBI-Project
 ┣ 📊 Credit_Card_Customer_Report.pbix      → Dashboard 1
 ┣ 📊 Credit_Card_Transaction_Report.pbix   → Dashboard 2
 ┣ 📂 Data
 ┃ ┣ 📄 credit_card.csv                    → Transaction-level data
 ┃ ┗ 📄 customer.csv                       → Customer demographic data
 ┣ 📂 Screenshots
 ┃ ┣ 🖼️ customer_report.png               → Dashboard 1 screenshot
 ┃ ┗ 🖼️ transaction_report.png            → Dashboard 2 screenshot
 ┗ 📄 README.md                            → This file
```

---

## ❓ Business Questions This Project Answers

**Customer Questions (Dashboard 1)**
- Which customer job group brings the most revenue to the business?
- Which age group uses credit cards the most?
- Do high-income customers contribute more than low-income customers?
- Are married or single customers more valuable?
- Which US cities have the most credit card customers?
- How has weekly revenue trended across the full year 2023?

**Transaction Questions (Dashboard 2)**
- Which card type (Blue, Silver, Gold, Platinum) generates the most revenue?
- Do customers prefer to swipe, use chip, or pay online?
- Which expense category (Bills, Fuel, Travel, etc.) drives the most spending?
- Which quarter was the strongest in 2023?
- Do car owners or non-car owners generate more interest for the business?

---

## 📸 Dashboard Screenshots

### Dashboard 1 — Credit Card Customer Report
![Customer Report](Screenshots/customer_report.png)

### Dashboard 2 — Credit Card Transaction Report
![Transaction Report](Screenshots/transaction_report.png)

---

## 🚀 How to Open and Use This Project

1. Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** — it is completely free
2. Download or clone this repository to your computer
3. Open the `.pbix` file in Power BI Desktop
4. If the data does not load, go to **Home → Transform Data → Data Source Settings** and update the file path to where you saved the CSV files
5. Click **Refresh** — all visuals will update automatically
6. Use the **slicers** (Gender, Quarter, Week) to filter and explore the data

---

## 💡 What I Learned Building This Project

- How to **connect and clean raw CSV data** using Power Query — handling missing values, wrong data types, and duplicate records
- How to write **DAX formulas** to calculate custom business KPIs that are not available in raw data
- How to design a **professional dark-theme dashboard** that is easy for non-technical stakeholders to read at a glance
- How to use **slicers and cross-filtering** to make dashboards fully interactive
- How to **sync two dashboards** so they tell a connected story rather than isolated reports
- How to extract **real business insights** from financial data and present them clearly
- How to think from a **business perspective** — not just showing data, but answering questions that matter to senior management

---

## 👤 About Me

I am a **Data Analyst** with skills in Power BI, SQL, Excel, and data visualization. I enjoy building dashboards that make complex data simple and help businesses make better decisions faster.

- 🔗 LinkedIn → *www.linkedin.com/in/dataanalyst-manish*
- 📧 Email → *alphainsinghts123@gmail.com*


---

## ⭐ Support This Project

If you found this project useful or learned something from it, please **give it a star ⭐** — it helps others find it too!

---

> *"The goal of a data analyst is not to show data. It is to tell the story that the data is trying to say."*
