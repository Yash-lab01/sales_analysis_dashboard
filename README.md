# 📊 Sales Analysis Dashboard — Power BI

A multi-page **Power BI dashboard** analyzing global sales performance across **147 countries** using the *Global Superstore* dataset (~51K+ orders, 2011–2014). Features two interactive pages — a **Sales Overview** with geographic and segment breakdowns, and a **Monthly & Yearly Sales Analysis** with time-series trends, category treemaps, and return tracking.

---

## 🖥️ Dashboard Preview

### Page 1 — Sales Overview
![Sales Overview Dashboard](screenshots/sales_overview.png)

### Page 2 — Monthly & Yearly Sales Analysis
![Monthly and Yearly Sales](screenshots/monthly_yearly_sales.png)

---

## 🎯 Dashboard Pages & Features

### Page 1 — Sales Overview
| KPI | Value |
|-----|-------|
| Sum of Sales | **418.62K** |
| Sum of Profit | **11.40K** |
| Sum of Quantity | **7,652** |
| Sum of Discount | **401.77** |
| Sum of Shipping Cost | **44.54K** |

- **Sales by City** — Donut chart showing revenue distribution across cities
- **Sales by Category** — Bar chart comparing Furniture, Technology, and Office Supplies
- **Sales by Segment** — Pie chart: Consumer (52.93%), Corporate (28.86%), Home Office (18.21%)
- **Sales by Sub-Category** — Horizontal bar chart highlighting top products (Chairs, Copiers, Bookcases, Phones, Appliances)
- **Geographic Map** — Interactive globe visualization with sales volume by region
- **Sales by Market, Year & Quarter** — Stacked area chart showing quarterly trends across markets (2011–2014)
- **Country Slicer** — Filter the entire page by country selection

### Page 2 — Monthly & Yearly Sales Analysis
| KPI | Value |
|-----|-------|
| Sum of Sales | **12.64M** |
| Sum of Profit | **1.47M** |
| Sum of Quantity | **178K** |
| Sum of Discount | **7.33K** |
| Count of Countries | **147** |
| Count of Returned | **1,173** |

- **Sales & Profit by Month** — Dual-axis bar & line chart comparing monthly sales vs. profit
- **Sales by Category & Sub-Category** — Treemap visualization (Technology, Furniture, Office Supplies with sub-categories)
- **Sales by Month** — Area chart with monthly sales trend line
- **Year Slicer** — Filter by year (2011, 2012, 2013, 2014)
- **Month Slicer** — Filter by individual month (January–December)

---

## 📁 Repository Structure

```
Sales-Analysis-Dashboard/
│
├── Global Superstore.xls      # Source dataset (Global Superstore)
├── sales_analysis.pbix         # Power BI dashboard file
├── screenshots/                # Dashboard screenshots for README
│   ├── sales_overview.png
│   └── monthly_yearly_sales.png
├── .gitignore                  # Git ignore rules
└── README.md                   # Project documentation
```

---

## 📊 Dataset

**Source:** Global Superstore dataset  
**Format:** Excel (`.xls`)  
**Records:** ~51,000+ orders across 147 countries

| Column | Description |
|--------|-------------|
| `Order ID` | Unique identifier for each order |
| `Order Date` | Date the order was placed |
| `Ship Date` | Date the order was shipped |
| `Ship Mode` | Shipping method (Standard, Second Class, First Class, Same Day) |
| `Customer Name` | Name of the customer |
| `Segment` | Customer segment (Consumer, Corporate, Home Office) |
| `Country` | Customer's country |
| `Market` | Global market region |
| `Region` | Sub-region within the market |
| `Product Name` | Name of the product |
| `Category` | Product category (Furniture, Office Supplies, Technology) |
| `Sub-Category` | Product sub-category |
| `Sales` | Revenue from the order |
| `Quantity` | Number of units ordered |
| `Discount` | Discount applied to the order |
| `Profit` | Profit earned from the order |
| `Shipping Cost` | Cost of shipping |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design, data modeling & visualization |
| **DAX** | Calculated measures, KPIs & time intelligence |
| **Power Query (M)** | Data cleaning, transformation & ETL |
| **Excel** | Source data format |

---

## 🚀 Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download from Microsoft)

### Steps to Open

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Yash-lab01/Sales-Analysis-Dashboard.git
   ```
2. **Open the dashboard:**
   - Launch **Power BI Desktop**
   - Open `sales_analysis.pbix`
3. **Refresh data (if needed):**
   - Go to **Home → Transform Data → Data Source Settings**
   - Update the file path to point to your local `Global Superstore.xls` file
   - Click **Refresh**

---

## 📌 Key Insights

- 📊 **Consumer segment dominates** — accounting for **52.93%** of total sales, followed by Corporate (28.86%) and Home Office (18.21%)
- 🪑 **Chairs lead sub-category sales** at **66K**, closely followed by Copiers and Bookcases at 63K each
- 📈 **Sales peak in November & December** — with **1.73M** and **1.75M** respectively, indicating strong seasonal/holiday demand
- 📉 **February is the weakest month** — recording only **0.61M** in sales across all years
- 🌎 **LATAM shows strong quarterly growth** — Q4 sales nearly doubled from 2011 to 2014
- 🔄 **1,173 orders were returned** across 147 countries — a metric worth monitoring for operational improvements
- 💰 **Profit margin is relatively thin** — total profit of **1.47M** on **12.64M** sales (~11.6%) suggests high discount impact (7.33K total discount)
- 🏢 **Technology category leads revenue** — with Phones (1.71M) and Copiers (1.51M) as top technology sub-categories

---

## 👤 Author

**Yash Bhawar**  
AI/ML Engineer & Data Analyst

[![GitHub](https://img.shields.io/badge/GitHub-Yash--lab01-181717?style=flat&logo=github)](https://github.com/Yash-lab01)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yash_Bhawar-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/yashbhawar)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  <i>If you found this project useful, consider giving it a ⭐!</i>
</p>
