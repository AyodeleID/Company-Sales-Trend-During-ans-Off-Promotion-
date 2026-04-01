<div align="center">

# 🛒 Company Sales Trend Analysis: Promotion vs Off-Promotion

### Revenue Dynamics, Customer Behavior, and Promotion Effectiveness Analytics

[![Excel](https://img.shields.io/badge/Excel-Advanced%20Analytics-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://microsoft.com/excel)
[![Python](https://img.shields.io/badge/Python-Supporting%20Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Time Series](https://img.shields.io/badge/Time%20Series-Trend%20%7C%20Seasonality-7C3AED?style=for-the-badge)](#)
[![Segmentation](https://img.shields.io/badge/Customer-Segmentation-0EA5E9?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Completed-16a34a?style=for-the-badge)](#)

<br/>

> A business analytics project that quantifies how promotions affect sales volume, revenue quality,  
> and customer purchase behavior—separating short-term lift from long-term value effects.

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Business Objective](#-business-objective)
- [Dataset](#-dataset)
- [Analytical Framework](#-analytical-framework)
- [Key Analyses](#-key-analyses)
- [Results & Insights](#-results--insights)
- [How to Use](#-how-to-use)
- [Visualization](#-visualization)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Practical Business Use Cases](#-practical-business-use-cases)
- [License](#-license)
- [Author](#-author)

---

## 🔍 Overview

This project examines how company sales performance changes between **promotion windows** and **regular (off-promotion) periods**.

The analysis focuses on:
- short-term volume effects,
- revenue quality,
- category-level differences,
- and customer response patterns.

The goal is to support better promotion planning and pricing strategy using evidence from transaction data.

---

## 🎯 Business Objective

To determine whether promotions create **incremental growth** or simply shift demand timing (cannibalization), and to identify which customer segments and product categories generate the best promotional ROI.

---

## 📦 Dataset

The input data consists of **daily transaction-level sales records**, including fields such as:

- `product_id`
- `category`
- `sales_date`
- `unit_price`
- `quantity`
- `customer_id` (if available)
- `is_promotion` (promo flag)

### Data Preparation Performed

- Removed duplicates
- Handled missing/null values
- Standardized date formats
- Validated category/product identifiers
- Created derived KPIs (revenue, basket metrics, promo-period tags)

---

## 🧪 Analytical Framework

```text
Raw Sales Transactions
          ↓
Cleaning + Feature Engineering
          ↓
Promo vs Off-Promo Split
          ↓
Descriptive + Time-Series + Segmentation
          ↓
Promotion Effectiveness Evaluation
          ↓
Business Recommendations
```

---

## 📊 Key Analyses

### 1. Descriptive Statistics
- Sales volume and revenue summaries by promo status
- Category-level performance comparison
- Distribution of basket size and order value

### 2. Time-Series Analysis
- Trend/seasonality decomposition
- Promo-window overlays on sales trajectory
- Short-term uplift vs post-promo normalization

### 3. Customer Segmentation

Behavioral grouping by promo response:
- Bargain Hunters
- Loyalists
- Occasional Deal Shoppers

Segment-level revenue contribution and sensitivity.

### 4. Promotion Effectiveness
- Conversion rate comparison (promo vs non-promo)
- Average order value (AOV) impact
- Revenue lift and margin-risk interpretation
- Cannibalization signal checks by category/segment

---

## 📌 Results & Insights

- Promotions generate clear short-term sales volume uplift
- Effect size differs significantly by product category
- Some categories/segments show cannibalization (promo purchases replacing regular purchases)
- High-response segments are not always high-profit segments
- Promotion success depends on targeting quality, not discount intensity alone

---

## ⚙️ How to Use

### 1. Open the workbook

Open the main Excel file:

```
company_sales_promotion_analysis.xlsx
```

All analysis, pivot tables, and charts are contained within named sheets.

### 2. Customize

- Update promo window definitions in the `Config` sheet
- Adjust segmentation rules in the `Segmentation` sheet
- Add your own KPI thresholds for your business context

### 3. Supporting Python scripts (optional)

If using supplementary Python scripts for data prep or additional modeling:

```bash
pip install -r requirements.txt
python analysis.py
```

---

## 🖼️ Visualization

Recommended visuals included in the workbook and `images/` folder:

- Sales trend over time with promotion windows shaded
- Promo vs off-promo revenue comparison bars
- Category lift heatmap
- Segment response distribution
- AOV and conversion side-by-side plots

Example markdown references:

```markdown
![Sales Trend](images/sales_trend.png)
![Promotion Comparison](images/promo_vs_offpromo.png)
```

---

## 📁 Project Structure

```
📦 company-sales-promotion-analysis
 ┣ 📄 README.md
 ┣ 📊 company_sales_promotion_analysis.xlsx
 ┣ 📄 requirements.txt
 ┣ 📂 data/
 ┃ ┣ 📄 sales_transactions.csv
 ┃ ┗ 📄 reference_tables.csv
 ┣ 📂 outputs/
 ┃ ┣ 📂 figures/
 ┃ ┗ 📂 tables/
 ┣ 📂 images/
 ┃ ┣ 📄 sales_trend.png
 ┃ ┗ 📄 promo_vs_offpromo.png
 ┗ 📂 src/
   ┣ 📄 preprocessing.py
   ┣ 📄 segmentation.py
   ┣ 📄 time_series.py
   ┗ 📄 promotion_effectiveness.py
```

---

## 🛠 Tech Stack

```text
Primary Tool:
- Microsoft Excel (Advanced Analytics)
  - PivotTables & PivotCharts
  - Power Query (data transformation)
  - Advanced formulas (INDEX/MATCH, SUMIFS, dynamic arrays)
  - Conditional formatting & dashboard design

Supporting Tools (optional):
- Python: pandas, numpy, matplotlib, seaborn, statsmodels, scipy
- Jupyter Notebook
```

---

## 💼 Practical Business Use Cases

- Promotion calendar optimization
- Discount strategy refinement by category
- Targeted campaign design by customer segment
- Revenue quality monitoring (volume vs value)
- Evidence-based trade marketing decisions

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

<div align="center">

**Ayodele Idowu**  
*Economist & Data Scientist*

[![GitHub](https://img.shields.io/badge/GitHub-AyodeleID-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AyodeleID)
[![Portfolio](https://img.shields.io/badge/Portfolio-ayodeleid.com-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://ayodeleid.com)

</div>
