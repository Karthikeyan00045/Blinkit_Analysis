# Blinkit Retail Performance Dashboard

An interactive, fully mobile-responsive Power BI dashboard analyzing grocery retail performance across outlets, product categories, and customer ratings, built on a dataset of 8,523 transaction records.

## Overview

This project transforms raw Blinkit retail data into a 10-page business intelligence dashboard designed for executive-level decision-making. It combines drill-through analysis, contextual tooltips, and rule-based conditional formatting to surface revenue trends, category performance, and outlet-level insights at a glance.

## Dataset

- **Source:** Blinkit grocery retail dataset
- **Size:** 8,523 records
- **Scope:** Outlet performance, product categories, fat content classification, item ratings, and sales trends across multiple years

## Dashboard Structure

The report is organized into six analytical pages, three contextual tooltip pages, and one drill-through page:

| Page | Purpose |
|---|---|
| **Overview** | Executive summary with headline KPIs (Total Sales, Total Products, Outlet Identifier, Item Type) |
| **KPI Summary** | Expanded KPI view including Revenue, Avg Sales per Item, and Rating |
| **Category Sales** | Category-level performance, including top and bottom-performing categories |
| **Outlet Analysis** | Outlet-by-outlet comparison of sales and distribution |
| **Fat & Year Trends** | Low Fat vs. Regular share analysis and year-over-year sales trends |
| **Ratings** | Item-level rating distribution and breakdown |
| **Tooltip Pages (×3)** | Custom hover tooltips for Category, Outlet, and Fat/Year visuals, giving contextual detail without navigating away from the main view |
| **Drill Through** | Dedicated detail page for outlet-level drill-down from any summary visual |

## Key Features

- **Mobile Layout Optimization:** Custom-designed phone layouts engineered for every single report view to deliver a true mobile-responsive executive experience.
- **12 custom DAX measures** powering KPIs, percentage calculations, and category rankings
- **Rule-based conditional formatting** on key metrics rather than static styling:
  - Total Sales: red below ₹150,000, green above ₹250,000, gradient between
  - Rating: red below 3.0, green above 4.5
  - Regular Share %: red below 40%, green above 60%
- **Drill-through navigation** from summary visuals into outlet-level detail
- **Custom report tooltips** on Category, Outlet Analysis, and Fat & Year Trends visuals
- **Cross-page navigation** via action buttons and a page navigator on the Overview page
- **Interactive slicers** for Item Type and other key dimensions, synced across relevant pages

## Tech Stack

- **Power BI Desktop** — report design, mobile responsive optimization, DAX modeling, and visualization
- **DAX** — custom measures for KPIs and conditional formatting logic
- **SQL** — upstream data cleaning, transformation, table joins, feature engineering, and exploratory data analysis prior to modeling

## Key Insights

- Total revenue across all outlets: **₹1,201,682**
- Top-performing product category: **Fruits and Vegetables (₹178,124)**
- Top-performing outlet format: **Supermarket Type1 (₹787,550)**
- Average item rating: **3.92**
- Low Fat vs. Regular product share: **64.60% Low Fat Share / 35.40% Regular Share**

## Screenshots

*(Add exported page screenshots here, e.g. `![Overview](screenshots/overview.png)`)*

## How to Use

1. Clone or download this repository.
2. Open `Blinkit_power_bi_dashboard.pbix` in [Power BI Desktop](https://microsoft.com) (free).
3. Use the page navigator on the Overview page to move between sections, or click any visual to drill through to outlet-level detail.
4. To view the mobile layout, publish the dashboard to Power BI Service or open it within the Power BI Mobile App.

## Repository Structure

├── Blinkit_power_bi_dashboard.pbix    
├── Main Power BI report file├── README.md                          
├── Project documentation└── screenshots/                       
├── Dashboard page screenshots (optional)


## Author

**Karthikeyan G**
Data Analyst | Power BI Certified (Besant Technologies, 2026)
[LinkedIn](#) · [GitHub](#)

## License

This project is for portfolio and educational purposes.
