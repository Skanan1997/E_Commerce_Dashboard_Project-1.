# E_Commerce_Dashboard_Project-1.

**E-Commerce Sales Dashboard Excel Project**

### Project Overview

**Project Title:** E-Commerce Sales Analysis Dashboard
**Level:** Beginner
**Tool:** Microsoft Excel (with Data Analysis Add-in)
**Dataset:** E-Commerce Dashboard Dataset.xlsx

This project focuses on building an interactive sales dashboard using Microsoft Excel. The dashboard provides a visual analysis of sales, profit, and product category trends. It involves cleaning and analyzing the data, summarizing it using pivot tables, and designing an intuitive interface with combo box controls and charts. This project is ideal for beginners looking to strengthen their Excel and data visualization skills.

---

### Objectives

* Clean and organize the sales dataset for analysis.
* Create month-wise and region-wise summaries of sales and profit.
* Develop interactive controls using combo boxes for product category filtering.
* Build a dynamic dashboard with charts and filters to visualize sales trends.
* Deliver a user-friendly and insightful dashboard.

---

### Project Structure

#### 1. Data Understanding & Setup

**Dataset Features:**
The dataset includes the following columns:

* Order ID, Order Date, Ship Date, Ship Mode
* Product Category, Product, Sales, Quantity
* Discount, Profit, Shipping Cost
* Order Priority, Customer ID, Customer Name
* City, State, Country, Region, Months

**Goal:** Analyze sales performance and trends by product category, region, and time.

---

#### 2. Data Preparation

* Load the dataset into Excel and format as an Excel Table.
* Convert date columns to proper date format.
* Extract **Month** from Order Date if not already available.
* Handle missing or inconsistent entries (if any).
* Create calculated fields (e.g., Profit Margin if needed).

---

#### 3. Data Analysis

* **Month-wise Sales and Profit Table:**
  Use a Pivot Table to summarize Sales and Profit by Month.

* **Region-wise Sales Table:**
  Use another Pivot Table to summarize Sales by Region.

* **User Control (Combo Box):**
  Insert a Combo Box from the Developer tab to select the **Product Category**.

  * Link it to a named range of unique product categories.
  * Use INDIRECT or formulas to dynamically update the charts based on selection.

---

#### 4. Visualization & Dashboard

* **Column Chart for Month-wise Sales & Profit:**

  * Linked to the month-wise Pivot Table.

* **Column Chart for Region-wise Sales:**

  * Linked to the region-wise Pivot Table.

* **Interactive Dashboard Elements:**

  * Combo Box for Product Category
  * Dynamic charts that update based on selection
  * Slicers (optional) for Order Priority or Region
  * KPIs like Total Sales, Total Profit, Avg. Shipping Cost

---

### Findings

* Identify which months and regions generated the highest sales.
* Discover which product categories are most profitable.
* Compare sales performance between different regions.
* Evaluate seasonal trends and customer behavior.

---

### Reports

* **Monthly Sales Report:** A breakdown of sales and profit trends per month.
* **Regional Sales Analysis:** Comparison of regions based on total sales.
* **Category Performance Overview:** Interactive insights based on selected category.
* **Customer Behavior:** Optional analysis based on customer segmentation.

---

### Conclusion

This Excel-based project provides an end-to-end walkthrough of analyzing e-commerce sales data and designing a fully functional dashboard. It combines analytical thinking with Excel tools to deliver actionable business insights. The final dashboard allows users to interactively explore sales trends and make data-driven decisions.

---

## Author - Kanan Sangeet

This project is part of my portfolio, demonstrating practical Excel skills in building business dashboards. Feel free to reach out for feedback, collaboration, or discussion.

