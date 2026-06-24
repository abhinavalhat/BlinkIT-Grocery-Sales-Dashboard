# 🛒 BlinkIT Grocery Sales Dashboard

An Excel-based sales analytics dashboard for BlinkIT grocery data, providing insights into product performance, outlet metrics, and customer ratings.

---

## 📊 Overview

This dashboard analyzes grocery sales data across multiple outlet types, locations, and product categories. It is built in Microsoft Excel with pivot-table-driven KPIs, charts, and slicers for interactive filtering.

---

## 📁 File Structure

The workbook (`BlinkIT_Grocery_Dashboard.xlsx`) contains three sheets:

| Sheet | Description |
|---|---|
| `Raw Data` | Source transaction-level data with item and outlet attributes |
| `Sheets Design` | Pivot tables and aggregations powering the dashboard visuals |
| `Dashboard` | Final interactive dashboard view with charts and KPI cards |

---

## 📋 Dataset Columns

The **Raw Data** sheet contains the following fields:

| Column | Description |
|---|---|
| `Sr.No` | Serial number / row identifier |
| `Item Fat Content` | Fat content label (`Low Fat`, `Regular`) |
| `Item Identifier` | Unique product code (e.g., `FDX32`) |
| `Item Type` | Product category (e.g., Snack Foods, Dairy, Frozen Foods) |
| `Outlet Establishment Year` | Year the outlet was established |
| `Outlet Identifier` | Unique outlet code (e.g., `OUT049`) |
| `Outlet Location Type` | Tier classification of the outlet location (`Tier 1`, `Tier 2`, `Tier 3`) |
| `Outlet Size` | Physical size of the outlet (`Small`, `Medium`, `High`) |
| `Outlet Type` | Type of store (`Grocery Store`, `Supermarket Type1/2/3`) |
| `Item Visibility` | Fraction of display area allocated to the item |
| `Item Weight` | Weight of the item (in kg) |
| `Sales` | Sales value for the item at the outlet |
| `Rating` | Customer rating (scale of 1–5) |

---

## 📈 Key Metrics (KPIs)

| Metric | Value |
|---|---|
| **Total Sales** | ₹8,383.33 |
| **Average Sales per Item** | ₹147.08 |
| **Number of Items** | 57 |
| **Average Customer Rating** | 4.06 / 5 |

---

## 🔍 Dashboard Insights

- **Sales by Fat Content:** Regular fat items outsell Low Fat items (₹4,555 vs ₹3,828)
- **Top Item Categories by Sales:** Snack Foods and Fruits & Vegetables lead revenue
- **Outlet Location:** All sampled data is from Tier 3 locations
- **Outlet Size:** Represented by Small outlets
- **Outlet Type:** Grocery Store
- **Establishment Year:** 2011

---

## 🛠️ Requirements

- **Microsoft Excel** 2016 or later (for full pivot table and slicer support)
- Alternatively: **LibreOffice Calc** (some features may vary)

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `BlinkIT_Grocery_Dashboard.xlsx` in Microsoft Excel.
3. Navigate to the **Dashboard** sheet to explore the visuals.
4. Use the slicers (filter controls) to drill down by outlet type, fat content, or location tier.
5. Raw data can be found in the **Raw Data** sheet for further analysis.

---

## 💡 Use Cases

- Retail sales performance analysis
- Product category benchmarking
- Outlet-level comparison across tiers and sizes
- Excel dashboard design reference / portfolio project

---

## 📌 Notes

- Some `Item Weight` values are missing in the raw data — this may affect weight-based analyses.
- `Item Fat Content` has minor inconsistencies (`low fat` vs `Low Fat`) that may need cleaning for extended analysis.

---

## 📄 License

This project is for educational and portfolio purposes. Data is sample/demo grocery sales data.
