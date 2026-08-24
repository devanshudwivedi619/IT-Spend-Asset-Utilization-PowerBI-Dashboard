# 💻 IT Spend & Asset Utilization Analytics Dashboard

**A Power BI dashboard that tracks IT software spending and license usage across departments to help companies cut unnecessary costs.**

![Dashboard Overview](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/dashboard-overview.png)

---

## 📌 Why I Built This

Many companies pay for hundreds of software licenses every year but never check how many of those licenses are actually being used. This leads to wasted money on subscriptions that sit idle.

**The goal of this project** was to build a dashboard that answers 5 simple business questions on one screen:

1. How much is the company spending on IT, and where does the money go?
2. Which department spends the most?
3. What percentage of purchased licenses are actually being used?
4. How many licenses are paid for but unused (wasted spend)?
5. Which software contracts are about to expire or have already expired?

This is a real problem faced by IT and Finance teams in every company. This dashboard is built to solve exactly that.

---

## 📊 Key Metrics (KPI Summary)

![KPI Summary](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/kpi-summary.png)

| Metric | Value |
|---|---|
| Total IT Spend | ₹5.51 Crore (₹55.17M) |
| Total Licenses Purchased | 9,025 |
| Overall License Utilization | 69.42% |
| Unused Licenses | 2,778 (≈31% of all licenses) |

---

## 🔍 Key Insights

- **IT Spend by Department:** HR has the highest annual spend at ₹1.09 Cr, followed by Customer Support (₹82L) and IT (₹74L). Marketing spends the least at ₹41L.

  ![IT Spend by Department](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/spend-by-department.png)

- **Spend by Category:** Software licenses make up the largest share of spend at 49.9% (₹2.75 Cr), followed by Hardware at 30.6% (₹1.69 Cr) and Cloud services at 19.5% (₹1.08 Cr).

  ![IT Spend by Category](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/spend-by-category.png)

- **Top Vendors:** Cisco is the highest-cost vendor (₹73.9L/year), followed by Dell (₹67.7L) and AWS (₹55.2L). These three vendors are the best candidates for contract renegotiation.

  ![IT Spend by Vendor](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/spend-by-vendor.png)

- **License Utilization Gap:** Out of 9,025 purchased licenses, only 6,247 are actually in use. That means **2,778 licenses (31%) are paid for but unused** — a direct, avoidable cost.

  ![License Utilization by Department](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/utilization-by-department.png)

- **Renewal Risk:** 178 contracts (59.3%) have already expired, and 85 (28.3%) are due for renewal soon. Only 37 (12.3%) are fully active. This means **nearly 88% of all IT contracts need immediate attention.**

  ![Asset Renewal Status](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/renewal-status.png)

- **Spend Trend:** Monthly IT spend fluctuates between ₹0.28M and ₹0.44M, with visible peaks in March and September, which is useful for budget forecasting.

  ![Monthly IT Spend Trend](https://github.com/devanshudwivedi619/IT-Spend-Asset-Utilization-PowerBI-Dashboard/blob/main/monthly-spend-trend.png)

---

## 🎯 Business Impact

If unused licenses (31% of the total) were cancelled or reassigned instead of renewed, the company could save a meaningful portion of the ₹5.51 Cr annual IT budget. This is the kind of cost-saving story this dashboard is designed to surface at a glance.

---

## 🗂️ Dataset

The dataset has 300 records of IT assets and software licenses, with these fields:

| Field | Description |
|---|---|
| Asset_ID | Unique ID for each license/asset |
| Software_Vendor | Vendor supplying the software (e.g., Cisco, Dell, AWS) |
| Category | Software, Hardware, or Cloud |
| Department | Department using the asset |
| Contract_Type | Monthly or Annual contract |
| Monthly_Cost_INR / Annual_Cost_INR | Cost of the license |
| Licenses_Purchased / Licenses_Used / Unused_Licenses | License counts |
| Utilization_Percentage | Percentage of purchased licenses actually used |
| Purchase_Date / Renewal_Date / Days_To_Renewal | Contract timeline |
| Renewal_Status | Active, Renewal Due Soon, or Expired |
| Payment_Status | Paid or Pending |
| Utilization_Status | High, Medium, or Low usage |

> This is a sample dataset created for portfolio and learning purposes.

---

## 🖥️ Dashboard Features

- **4 KPI cards** for a quick spend and utilization summary
- **6 interactive charts** covering spend, category, vendor, utilization, and renewal status
- **5 slicers** (Department, Category, Contract Type, Payment Status, Renewal Status) so any user can filter the entire dashboard instantly — for example, viewing only the Finance department's numbers with one click

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — dashboard design and data modeling
- **DAX** — calculated measures for Total Spend, Utilization %, and Unused Licenses
- **Power Query** — data cleaning and transformation before loading
- **Data Visualization** — chart selection and layout for fast, clear reading

---

## 📂 How to View This Project

1. Download It Spend & Asset Utilization Analytics Dashboard Project.pbix
    from this repository.
3. Open it in Power BI Desktop (free to download from Microsoft).
4. If you don't have Power BI installed, just scroll up — all charts are shown as images above.

---

## 👤 About Me

**Devanshu Dwivedi** — Data Analyst | Power BI | Excel | SQL

🔗 GitHub: [github.com/devanshudwivedi619](https://github.com/devanshudwivedi619)
