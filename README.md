
# 📊 Leads Calling Dashboard - Power BI

## 📌 Project Overview

The **Leads Calling Dashboard** is an interactive Power BI dashboard designed to monitor and analyze the performance of a leads calling process. It provides a clear overview of customer responses, conversion metrics, city-wise analysis, and sector-wise performance, helping businesses make informed decisions.

This dashboard transforms raw calling data into meaningful insights through interactive visualizations and KPI metrics.

---
## 🎯 Project Objective

The objective of this project is to monitor lead calling performance and analyze customer interest and conversion rates across different cities and sectors.

## 🚀 Key Features

- 📞 Total Leads Called
- ✅ Total Interested Leads
- ❌ Total Not Interested Leads
- 📈 Conversion Rate KPI
- 🍩 Response Breakdown (Donut Chart)
- 📅 Calling Date Trend Analysis
- 🏙️ City-wise Response Analysis
- 🏢 Sector-wise Performance Analysis
- 🎛️ Interactive Filters (Calling Date, City, Category)

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Microsoft Excel

---
## 📊 Power BI Dashboard

The Power BI dashboard file is included in this repository:

**[Download Power BI Dashboard](./Leads%20Calling%20Dashboard.pbix)**

## 📊 KPIs Used

- Total Leads Called
- Total Interested
- Total Not Interested
- Conversion Rate

---

## 📁 Project Structure

```text
sales-calling-dashboard/
│
├── Leads Calling Dashboard.pbix
├── Leads Calling Dashboard.png
├── Dataset/
│   └── sales_calling_data.xlsx
└── README.md
```

## 📷 Dashboard Preview

![Sales Calling Dashboard](Leads%20Calling%20Dashboard.png)

## 📈 DAX Measures Used

Some of the DAX measures created in this project include:

- Total Leads Called
- Total Interested
- Total Not Interested
- Conversion Rate

Example:

```DAX
Conversion Rate =
DIVIDE(
    [Total Interested],
    [Total Leads Called],
    0
)
```

---

## 🎯 Business Use Case

Businesses receive hundreds or thousands of leads every day. Instead of reviewing raw data manually, this dashboard provides a single-page interactive report that enables managers to monitor calling performance, customer responses, and conversion rates efficiently.

---

## 🛠️ Skills Demonstrated

- Data Cleaning & Transformation
- Power Query
- Data Modeling
- DAX
- KPI Development
- Data Visualization
- Dashboard Design

---

## 👨‍💻 Author

**Rohit Shah**

📧 Email: rohitlal2334@gmail.com

🔗 LinkedIn: www.linkedin.com/in/rohit-lal1827

---

⭐ If you found this project helpful, feel free to star this repository.
