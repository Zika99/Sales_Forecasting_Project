# Sales_Forecasting_Project

# 📈 BrightMart Retail Sales Forecast Engine

> A beginner-friendly Python project that simulates a retail sales forecasting and inventory management system using Python fundamentals.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Overview

The **BrightMart Sales Forecast Engine** is a Python-based sales analytics project developed to simulate how retail organizations monitor weekly sales performance, forecast future revenue, evaluate inventory levels, and support business decision-making.

The project was built using only fundamental Python concepts, making it an excellent demonstration of how core programming skills can be applied to solve real-world retail business problems.

The analysis covers revenue generation, inventory management, sales forecasting, promotion eligibility, and demand forecasting while producing a professionally formatted sales report.

---

# 🎯 Project Objectives

The objectives of this project are to:

- Calculate weekly sales revenue
- Forecast next week's sales
- Forecast next week's revenue
- Update inventory after weekly sales
- Determine whether sales targets were achieved
- Identify products requiring restocking
- Evaluate promotion eligibility
- Predict future product demand
- Generate a professional business report

---

# 🛠 Technologies Used

- Python 3
- Variables
- Data Types
- Arithmetic Operators
- Assignment Operators
- Comparison Operators
- Logical Operators
- f-Strings
- Multiline Strings

---

# 📂 Project Structure

```
BrightMart-Sales-Forecast-Engine/
│
├── sales_forecast.py
├── README.md
├── .gitignore
└── LICENSE
```

---

# 🏪 Business Scenario

BrightMart Retail Stores wants to monitor product performance every week.

Management needs answers to important business questions such as:

- How much revenue was generated?
- Was the weekly sales target achieved?
- Does inventory need replenishment?
- Should this product be promoted?
- Is customer demand expected to increase next week?

This project automates these calculations using Python.

---

# ⚙ Methodology

The project follows a simplified retail sales analytics workflow.

### 1. Data Collection

Product information was stored using Python variables.

The dataset included:

- Product Name
- Selling Price
- Units Sold
- Weekly Sales Target
- Forecast Growth Rate
- Current Stock
- Minimum Stock Level
- Product Availability

---

### 2. Revenue Analysis

Weekly revenue was calculated as:

```
Revenue = Selling Price × Units Sold
```

---

### 3. Sales Forecasting

Projected weekly sales were estimated using a forecast growth rate.

```
Forecast Sales =
Units Sold + (Units Sold × Growth Rate ÷ 100)
```

---

### 4. Revenue Forecasting

Expected revenue for the following week was estimated using forecasted sales.

```
Forecast Revenue =
Forecast Sales × Selling Price
```

---

### 5. Inventory Analysis

Inventory levels were updated after deducting weekly sales.

The remaining inventory was then compared with the minimum stock level to determine whether restocking was required.

---

### 6. Business Decision Analysis

Logical and comparison operators were used to determine:

- Sales target achievement
- Restocking requirements
- Promotion eligibility
- High-demand products

---

### 7. Reporting

The final output was presented using a professional multiline f-string report.

---

# 📊 Sample Output

```
=================================================
        BRIGHTMART SALES FORECAST REPORT
=================================================

Product Name           : Wireless Mouse

Selling Price          : ₦12,500.00

Units Sold This Week   : 180

Weekly Revenue         : ₦2,250,000.00

Forecast Growth Rate   : 15%

Forecast Sales         : 207 Units

Forecast Revenue       : ₦2,587,500.00

Current Stock          : 70 Units

Sales Target Achieved  : False

Restocking Required    : True

Product Available      : True

Promotion Eligible     : False

High Demand Forecast   : True

=================================================
```

---

## Sample Output

<p align="center">
<img width="1241" height="703" alt="BrightMart1" src="https://github.com/user-attachments/assets/765e2511-a5a1-44f7-820f-762e5243f031" />
<img width="1276" height="658" alt="BrightMart2" src="https://github.com/user-attachments/assets/35c35455-c388-4dec-a003-b4dc9bef658c" />
<img width="790" height="652" alt="BrightMart3" src="https://github.com/user-attachments/assets/8f14ed71-6202-431e-a805-ccfaed84f6d4" />
<img width="735" height="659" alt="BrightMart4" src="https://github.com/user-attachments/assets/d163ac4e-af92-4081-97f8-57693ec47207" />
<img width="658" height="649" alt="BrightMart5" src="https://github.com/user-attachments/assets/aec98a4a-5b45-41d5-a59f-aa13c9dd9bf3" />
        
</p>


# 📈 Key Findings

From the analysis, the following insights were obtained:

- Weekly revenue generated was **₦2,250,000.00**
- Forecasted sales increased from **180 units** to **207 units**
- Forecasted revenue increased to **₦2,587,500.00**
- Inventory fell below the minimum stock level after sales
- The weekly sales target was not achieved
- The product qualified as a high-demand product based on projected sales and revenue

---

# 🚀 Bonus Challenge – Multi-Product Analysis

The project was extended to analyze a second product using the same business rules.

## Product 1

| Attribute | Value |
|------------|-------|
| Product | Wireless Mouse |
| Selling Price | ₦12,500 |
| Units Sold | 180 |
| Weekly Target | 200 |
| Forecast Growth | 15% |
| Current Stock | 250 |
| Minimum Stock | 100 |
| Available | True |

---

## Product 2

| Attribute | Value |
|------------|-------|
| Product | Bluetooth Speaker |
| Selling Price | ₦35,000 |
| Units Sold | 95 |
| Weekly Target | 100 |
| Forecast Growth | 20% |
| Current Stock | 140 |
| Minimum Stock | 80 |
| Available | True |

---

The same analysis was performed for both products.

The following metrics were calculated:

- Weekly Revenue
- Forecast Sales
- Forecast Revenue
- Updated Stock
- Sales Target Achievement
- Restocking Requirement
- Promotion Eligibility
- High Demand Forecast

---

# 📊 Product Comparison

| Business Question | Result |
|------------------|--------|
| Which product generated more revenue? | Bluetooth Speaker |
| Which product has the higher forecasted revenue? | Bluetooth Speaker |
| Which product requires restocking? | Both products |
| Which product is expected to have higher demand next week? | Both products |
| Which product should management prioritize? | Bluetooth Speaker |

---

# 💡 Business Insights

The comparative analysis revealed that:

- Although the **Wireless Mouse** sold more units, the **Bluetooth Speaker** generated significantly more revenue because of its higher selling price.

- Both products require inventory replenishment after weekly sales.

- Both products satisfy the high-demand criteria for the following week.

- The **Bluetooth Speaker** generates the highest current and projected revenue and should therefore receive greater marketing attention.

- Continuous monitoring of inventory and sales trends can improve operational planning and reduce stock shortages.

---

# ✅ Recommendations

Based on the findings, BrightMart should consider the following actions:

- Restock both products immediately to prevent inventory shortages.
- Increase inventory levels before the forecasted rise in demand.
- Investigate why the weekly sales targets were not achieved.
- Prioritize marketing campaigns for the Bluetooth Speaker because of its higher revenue potential.
- Continue tracking weekly sales performance to improve forecasting accuracy.
- Consider implementing automated reporting for faster business decision-making.

---

# ⚠ Limitations

This project was intentionally developed using only Python fundamentals.

Current limitations include:

- Data is hardcoded instead of being loaded from external sources.
- Only two products were analyzed.
- Forecasting uses a fixed percentage growth rate rather than historical sales trends.
- No data visualization was included.
- No database integration.
- No user input validation.
- No exception handling.
- No file export functionality.

---

# 🔮 Future Improvements

Potential improvements include:

- Reading sales data from CSV or Excel files using **Pandas**
- Supporting unlimited products
- Creating interactive dashboards using **Power BI** or **Streamlit**
- Visualizing sales trends with **Matplotlib**
- Using historical sales data for predictive forecasting
- Connecting to SQL databases
- Exporting reports to Excel and PDF
- Building a web-based inventory management system

---

# 🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

- Python Programming
- Variables and Data Types
- Arithmetic Operations
- Assignment Operators
- Comparison Operators
- Logical Operators
- Business Logic
- Retail Analytics
- Revenue Forecasting
- Inventory Management
- Sales Analysis
- Professional Report Generation
- Problem Solving

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Translating business requirements into Python code
- Performing retail sales calculations
- Forecasting sales and revenue
- Applying logical reasoning to business decisions
- Writing clean and readable Python code
- Documenting projects professionally using GitHub Markdown

---

# 👩🏽‍💻 Author

**Ngozi Bridget**

Pharmacist | Aspiring Data Analyst & Data Engineer

Passionate about using data to solve business and healthcare problems through analytics, automation, and technology.

- 💼 LinkedIn: *(https://www.linkedin.com/in/ngozi-okoronkwo-49a2b923a?)*
- 🐙 GitHub: *(github.com/Zika99)*

---


