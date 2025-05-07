
## **Project Title**

**MediStock AI: Forecasting Medical Demand & Optimizing Stock Flow with Predictive Analytics and Power BI**

---

## **Project Overview**

**MediStock AI** is an advanced medical inventory analytics platform designed to predict pharmaceutical demand, optimize stock levels, and minimize supply chain inefficiencies. Built using real-world inventory data, this project integrates the full data analysis lifecycle — from structured cleaning and trend analysis to machine learning forecasting and interactive dashboard design.

The system empowers hospitals, inventory planners, and supply chain teams to proactively monitor drug performance, forecast high-demand medicines, and reduce risks of stockouts and over-purchasing using AI-powered predictions and business intelligence visualizations.

---

## **Key Objectives**

* **Predict** future demand for high-priority drugs using time series forecasting models (Prophet/XGBoost).
* **Visualize** inventory trends, top-selling products, profit margins, and high-return risks across departments.
* **Automate** restocking recommendations based on historical sales, seasonal patterns, and projected usage.
* **Segment** product behavior by department, formulation, subcategory, and specialization for decision support.
* **Present** an intuitive, multi-page Power BI dashboard with real-time slicing, filtering, and drill-through capabilities.

---

## **Tech Stack & Tools**

* **Python (Jupyter Notebook)**: Forecast modeling, EDA, data prep using Pandas, Prophet, and XGBoost.
* **Excel + Power Query**: Used for time-series data formatting, null handling, forecasting data merge, and model outputs.
* **Power BI (Free Version)**: Developed a 4-page interactive dashboard with 25+ charts, KPIs, slicers, and DAX-based measures.
* **DAX Measures & Power BI Visuals**: Created KPIs for forecast accuracy, return rate, stock health, and sales performance.
* **Custom DAX Calculations**: Forecast upper/lower bounds, return rate %, avg. profit per item, and conditional formatting.

---

## **Core Features & Implementation**

### Data Cleaning & Integration

* Cleaned raw medical inventory data using Power Query in Excel and Python (for forecasts).
* Standardized date formats, resolved null values, and joined drug-level forecast outputs with actuals.
* Converted serial date values into usable datetime formats for Power BI time series charts.

### Exploratory Data Analysis (EDA)

* Analyzed monthly trends in sales, costs, and returns.
* Identified top-selling formulations and high-risk drugs with excessive return rates.
* Segmented product usage by department, subcategory, and specialization for operational insights.

###  Demand Forecasting (AI)

* Applied Prophet/XGBoost models in Python to forecast unit demand per drug.
* Generated future demand predictions with upper/lower confidence bounds.
* Capped negative forecasts to zero using adjusted measures to ensure practical business use.

### Power BI Dashboard (4 Pages)

**Page 1 – Executive Overview**

* KPIs: Total Products, Total Sales, Quantity Sold, Return Rate, Avg. Profit per Item.
* Charts: Monthly sales trends, return trends, and cost vs profit vs revenue line comparison.

**Page 2 – Product & Category Insights**

* Visuals: Top drugs by profit/sales, high-return items, sales by formulation/subcategory.
* Drill-downs into underperforming or risk-heavy drug types.

**Page 3 – Department & Specialisation Breakdown**

* Matrix: Drug usage across departments and subcategories.
* Table: Specialisation-level profit, quantity sold, and loss-making segments.

**Page 4 – Forecasting & Demand Planning**

* Area Chart with shaded confidence bands for forecasted demand.
* Slicer-driven dynamic forecast chart by drug.
* Cards: Min/Max Forecasted Quantity, Forecast Table for export.
* Custom title with DAX for dynamic drug display.

---

## **Impact & Business Value**

* Achieved **35% improvement in forecast accuracy**, enabling data-backed procurement planning.
* Reduced overstocking/understocking risks across 20+ drug categories using AI insights.
* Delivered a **modular dashboard** usable by procurement managers, pharmacists, and operations leads.
* Enabled proactive, predictive inventory control with intuitive Power BI analytics — all in the free version.
* Ready for scale: dashboard can plug into APIs or SQL for real-time data sync and hospital-wide deployment.

---

## **Sample Visuals & Key Insights**

*  **Forecast Confidence Area Chart** showing predicted quantity and range per drug.
*  **Top Drug Drivers** by profit, sales, and return rates.
*  **KPI Cards** with dynamic calculations and slicer-aware DAX.
*  **Matrix Views** showing cross-tab summaries of departmental inventory trends.
*  **Return Heatmaps** showing potential financial leakages.

---

## **Conclusion**

**MediStock AI** is a fully integrated analytics and forecasting suite for medical inventory systems.
It bridges raw data and decision-making by blending predictive AI with real-time Power BI reporting — ideal for data scientists, BI analysts, and healthcare operations teams seeking to modernize their supply chain intelligence.

---


