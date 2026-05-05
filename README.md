## 👋 About Me

Hi! I'm **Susan Njeri Ng'ang'a** — a data analytics professional based in **Nairobi, Kenya** 🇰🇪, with a BSc in Information Technology from **KCA University** and currently completing an advanced **Data Analytics program at Lux Tech Academy**.

I specialize in transforming messy, complex datasets into clear, actionable insights through SQL, Power BI dashboards, and Python analysis. My work spans financial data, network operations monitoring, and AI research.

- 🔭 Currently building out my data analytics portfolio with real-world SQL projects
- 🌱 Deepening skills in **advanced PostgreSQL**, **Python for data**, and **cloud BI**
- 💼 Actively seeking roles in **Data Analytics**, **Business Intelligence**, or **SQL/BI Development**
- 🤝 Open to collaborations on data-driven projects across Kenya and Africa
- ⚡ Fun fact: I also run **Yalara**, a natural herbal hair oil brand — data and entrepreneurship go hand in hand!

---

## 🛠️ Tech Stack

**Databases & Query**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=databricks&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-372923?style=flat-square&logo=dbeaver&logoColor=white)

**Business Intelligence & Visualization**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

**Programming & Analytics**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Cloud & Tools**

![Aiven](https://img.shields.io/badge/Aiven-FF3E00?style=flat-square&logo=aiven&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 📂 Featured Projects

### 🔷 [Sales Performance Dashboard](https://github.com/your-username/sales-dashboard)
> **Power BI · PostgreSQL · Aiven Cloud · DAX**

End-to-end BI dashboard connected live to a cloud PostgreSQL database. Tracks revenue, customer retention, and inventory turnover with drill-down filters by region and product category.

---

### 🔷 [E-commerce Database Schema & SQL Analytics](https://github.com/your-username/ecommerce-sql)
> **PostgreSQL · CTEs · Window Functions · DBeaver**

Designed a fully normalized relational schema (customers, products, sales, inventory) and wrote 40+ analytical queries — including window functions, subqueries, rank/dense_rank, running totals, and cohort-style analysis.

```sql
-- Example: Top customers by revenue using window functions
SELECT
    customer_name,
    total_spent,
    RANK() OVER (ORDER BY total_spent DESC) AS revenue_rank,
    ROUND(total_spent / SUM(total_spent) OVER () * 100, 2) AS pct_of_total
FROM customer_summary;
```

---

### 🔷 [Customer Segmentation Analysis](https://github.com/your-username/customer-segmentation)
> **SQL · Window Functions · CTEs · PostgreSQL**

Segmented customers by lifetime value, recency, and frequency using advanced SQL. Surfaced that the top 20% of customers contributed 78% of total revenue — presented as an actionable BI report.

---

### 🔷 [Power BI + PostgreSQL Connection Guide](https://github.com/your-username/powerbi-postgres-guide)
> **Power BI Desktop · JDBC · Aiven Cloud · DBeaver**

Practical reference guide documenting how to connect Power BI Desktop to both local and Aiven-hosted PostgreSQL instances, covering JDBC setup, DirectQuery vs Import modes, and troubleshooting common issues.

---

## 💼 Experience

| Period | Role | Organization |
|---|---|---|
| 2024 – Present | Data Analytics Student | Lux Tech Academy |
| 2024 | Power BI Dashboard Intern | ICT Authority – Network Operations Centre |
| 2024 | Data & AI Research Attachment | Africa AI Labs |
| Prior | IT Support | Hammers General Hardware |


## 🎯 Currently Learning

- 📐 Statistics for data science (normal distributions, variance, estimated parameters)
- 🐍 Python data analysis — pandas, matplotlib, NumPy
- 🌐 Building end-to-end data pipelines from PostgreSQL → Power BI → stakeholder reports
- ☁️ Cloud data tools on AWS and Azure (in progress)
