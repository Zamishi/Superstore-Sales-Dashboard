# Superstore Sales Dashboard 📊

An interactive business analytics dashboard built using Microsoft Excel and Power BI to uncover insights from Superstore retail data.

---

## 📌 Project Overview

This project demonstrates how sales performance, profitability, and key trends can be visualized effectively using Excel preprocessing and Power BI dashboarding. It provides decision-makers with actionable KPIs and segment-level insights.

---

## 🧰 Tools & Technologies Used

- **Microsoft Excel** – For data cleaning and transformation using Power Query Editor.
- **Microsoft Power BI** – For building dynamic dashboards with interactive slicers and charts.
- **Power Query Editor** – For preprocessing the raw dataset.
- **Data Analysis Techniques** – KPI calculations, trend analysis, category-wise performance.

---

## 🧽 Data Cleaning & Preprocessing (Excel + Power Query)

The original Superstore dataset contained inconsistencies and required shaping before analysis. Here's how the preprocessing was done:

### ✅ Steps Performed in Power Query Editor:

1. **Removed Unnecessary Columns:**
   - Dropped fields like Postal Code and Country which had no variance.

2. **Handled Missing Values:**
   - Filtered out rows with missing `Order Date`, `Sales`, or `Category`.

3. **Changed Data Types:**
   - Converted `Order Date` and `Ship Date` to proper Date format.
   - Changed `Quantity` and `Profit` to numeric types.

4. **Created New Columns:**
   - Extracted **Year** and **Month** from `Order Date` for trend analysis.
   - Added `Profit Margin` column using:  
     `Profit Margin = (Profit / Sales) * 100`

5. **Normalized Categories:**
   - Corrected inconsistencies in `Segment` and `Category` naming.
   - Ensured all textual columns were trimmed and properly cased.

6. **Loaded Clean Data into Power BI:**
   - Final preprocessed table was loaded directly into Power BI for visualization.

---

## 📈 Dashboard Features

- **KPIs:** Total Sales, Profit, Quantity Sold, Average Profit Margin.
- **Dynamic Filters:** Region, Segment, Category, Sub-Category.
- **Time Series Charts:** Monthly trends in sales and profit.
- **Top N Visuals:** Most profitable sub-categories and highest-selling items.

  <img width="1992" height="1105" alt="image" src="https://github.com/user-attachments/assets/45361b08-44a1-4abe-8822-8a8c637be233" />


---

## 📂 Files Included

- `Superstore.xlsx` – Cleaned dataset with Power Query transformation steps.
- `Superstore Dashboard.pbix` – Power BI file with interactive visualizations.

---

## 🧠 Key Insights

- **Western Region** showed consistently high sales but lower profit margins.

  <img width="2848" height="1209" alt="image" src="https://github.com/user-attachments/assets/ab83fcab-f014-4fe0-a3a9-313ead45d37f" />

- **Technology Segment** was the most profitable across all regions.
- **Tables and Bookcases** performed poorly despite high order volumes.

  <img width="2876" height="1219" alt="image" src="https://github.com/user-attachments/assets/a72eac3d-7cf2-449e-9a18-56e1bd466dea" />

- Clear monthly seasonality in order trends, especially Q4 spikes.

  <img width="2856" height="1170" alt="image" src="https://github.com/user-attachments/assets/2d053c7f-73a2-4cf9-8a83-0aaf948a8867" />


---

## 🚀 How to Use

1. Clone this repo or download the files.
2. Open `Superstore Sales Dashboard.pbix` in Power BI.
3. Interact with slicers to explore sales by segment, category, region, and time.
4. Optional: View Power Query steps within Power BI or Excel’s Query Editor.

---

## 📜 License

This project is provided for educational and demonstration purposes only.
