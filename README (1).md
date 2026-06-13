# 👩‍💻 Customer Behavior Data Analysis

An end-to-end data analytics project that walks through the complete workflow of transforming raw retail customer data into actionable business insights — using Python, SQL, and Power BI.

---

## 📌 Project Overview

This project simulates a real-world corporate analytics workflow. Starting from raw data, it covers every stage: cleaning, modeling, querying, and visualizing — culminating in a dashboard that helps stakeholders make data-driven decisions.

The analysis focuses on:
- Understanding customer shopping behavior and purchase patterns
- Identifying customer segments based on loyalty and spend
- Surfacing key drivers of customer retention and revenue

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy, Matplotlib) | Data cleaning, EDA, and loading data into SQL |
| SQL (MySQL / PostgreSQL / MS SQL Server) | Business queries and insight extraction |
| Power BI | Interactive dashboard and visual storytelling |

---

## 🔄 Project Workflow

### 1. 🧹 Data Preparation & EDA — Python
- Imported and explored the raw dataset
- Handled missing values, duplicates, and data type corrections
- Performed Exploratory Data Analysis (EDA) to understand distributions and outliers
- Loaded the cleaned data into a SQL database via Python

**Notebook:** `Customer_Shopping_Behavior_Analysis.ipynb`

### 2. 🗄️ Data Analysis — SQL
- Created and queried a relational database
- Answered key business questions around:
  - Customer segmentation
  - Loyalty and repeat purchase behavior
  - Revenue trends by category, region, and season
- Simulated business transaction scenarios using SQL queries

**File:** `customer_behavior_sql_queries.sql`

### 3. 📊 Visualization & Dashboard — Power BI
- Connected Power BI directly to the SQL database
- Built an interactive dashboard with filters for segment, region, and time
- Highlighted key patterns: top customer segments, purchase frequency, revenue drivers

**File:** `customer_behavior_dashboard.pbix`

---

## 🚀 How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/syamala4428/<repo-name>.git
   cd <repo-name>
   ```

2. **Run the Python notebook**
   - Open `Customer_Shopping_Behavior_Analysis.ipynb`
   - Execute cells for data import, cleaning, EDA, and SQL data loading

3. **Set up the SQL database**
   - Create a database in MySQL / PostgreSQL / MS SQL Server
   - Run the Python notebook to load data into your database
   - Open `customer_behavior_sql_queries.sql` and run the business queries

4. **Open the Power BI dashboard**
   - Open `customer_behavior_dashboard.pbix`
   - Connect it to your SQL database
   - Explore the interactive visuals

---

## 📁 Repository Structure

```
├── Customer_Shopping_Behavior_Analysis.ipynb   # Python EDA & data loading
├── customer_behavior_sql_queries.sql           # SQL business queries
├── customer_behavior_dashboard.pbix            # Power BI dashboard
└── README.md
```

---

> Built by **Syamala** | [GitHub](https://github.com/syamala4428)
