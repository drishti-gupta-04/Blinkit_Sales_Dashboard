# 🛒 Blinkit Sales Analysis Dashboard

An interactive Power BI dashboard analyzing Blinkit grocery sales to uncover insights on item performance, outlet types, outlet locations, fat content and customer ratings.

![Dashboard](Dashboard%20Image.png)

## 📌 Project Overview

This project simulates a real-world retail analytics workflow — from raw grocery sales data to an interactive Power BI dashboard used to track product and outlet performance.

**Business questions answered:**

- Which item types and fat-content categories drive the most sales?
- Which outlet types, sizes and location tiers perform best?
- How do average sales, item counts and ratings compare across outlet types?
- How have sales changed by outlet establishment year?

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power Query** | Data cleaning and transformation |
| **DAX** | Custom measures for Total Sales, Average Sales, No. of Items and Avg Rating |
| **Power BI** | Data modeling and interactive dashboard design |
| **Excel** | Source dataset and initial data inspection |

## 📊 Dashboard Sections

| Section | Description |
|---------|-------------|
| **KPI Cards** | Total Sales, Average Sales, No. of Items and Avg Rating at a glance |
| **Fat Content** | Low Fat vs Regular share of sales, and fat content by outlet tier |
| **Item Type** | Sales by item type, from Fruits and Vegetables down to Seafood |
| **Outlet Establishment** | Sales trend by outlet establishment year (2012 to 2022) |
| **Outlet Size & Location** | Sales by outlet size and by location tier (Tier 1, 2, 3) |
| **Outlet Type** | Total sales, items, average sales, rating and item visibility by outlet type |
| **Filter Panel** | Slicers for Outlet Location Type, Outlet Size and Outlet Item Type |
| **Metric Toggle** | Switch charts between Total Sales, Average Sales, No. of Items and Avg Rating |
| **Info Button** | Project details popup built using bookmarks |

## 🔎 Key Insights

- Total sales stand at **₹1.20M** across **8,523 items**, with an average sale of **₹141** and an average rating of **3.9**.
- **Fruits and Vegetables** and **Snack Foods** are the top item types at about ₹0.18M each, followed by Household and Frozen Foods.
- **Low Fat** items drive about 65% of sales (₹776.32K), well ahead of Regular items.
- **Supermarket Type1** contributes about 66% of total sales (₹787.55K), far ahead of Grocery Store, Type2 and Type3, which sit between ₹130K and ₹152K each.
- **Tier 3** locations lead in sales (₹472.13K), followed by Tier 2 (₹393.15K) and Tier 1 (₹336.40K).
- **Medium-sized** outlets contribute the most sales (₹507.90K), ahead of Small and High.
- Sales by outlet establishment year peak in **2018 (₹205K)**, against roughly ₹130K in most other years.
- Average rating stays at **3.9** across all outlet types, so ratings do not separate outlet performance.

## 🎯 Skills Demonstrated

- Data cleaning and transformation (Power Query)
- DAX measure creation
- Interactive dashboard design (slicers, KPI cards, bookmarks)
- Business-focused KPI selection and storytelling

## 📁 Repository Structure

```
Blinkit_Sales_Dashboard/
├── README.md
├── Blinkit Dashboard PB.pbix
├── Dashboard Image.png
└── Dataset (Blinkit Grocery ).xlsx
```

## 📝 Data Notes & Limitations

This dashboard is built on a Blinkit grocery sales dataset for learning and portfolio purposes — it does not represent real Blinkit operational data.

- Average rating is 3.9 for every outlet type, which suggests ratings in the source data are fairly uniform, so rating is a weak differentiator here.
- The establishment chart shows sales by the year an outlet was established, not sales over time, so it should not be read as a revenue timeline.

## 🚀 How to Use

1. Download `Blinkit Dashboard PB.pbix`
2. Open it in Power BI Desktop (free download from Microsoft)
3. Use the filter panel and metric toggle to explore the data interactively
4. Click the **i** button (Ctrl + click in Desktop) to view project details

## 👤 Author

**Drishti Gupta**

*This project was built for educational and portfolio purposes.*
