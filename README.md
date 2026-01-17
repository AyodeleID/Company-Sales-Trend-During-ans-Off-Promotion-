# Company Sales Trend Analysis During and Off Promotion

## Overview
This project analyzes how sales of a company vary during promotional campaigns versus off‑promotion periods. By examining transaction‑level data, we identify patterns in revenue, customer behaviour, and the effectiveness of promotions.

## Data
The dataset contains daily sales records with fields such as product ID, category, sales date, unit price, and whether the transaction occurred during a promotion. Data cleaning steps included removing duplicates, handling missing values, and standardizing date formats.

## Analysis
- **Descriptive statistics:** Summaries of sales volume and revenue during and off promotions.
- **Time‑series analysis:** Trend and seasonality decomposition to understand underlying patterns.
- **Customer segmentation:** Grouping customers based on their response to promotions (e.g. bargain hunters vs loyalists).
- **Promotion effectiveness:** Comparing key metrics (conversion rate, average order value) across promotional periods.

## Results
The study reveals that promotions drive a significant short‑term lift in sales volume, but the effect varies across product categories. Some segments exhibit cannibalization where promotion‑driven purchases replace regular purchases. Visualizations of sales trends and promotion windows illustrate these dynamics.

## Usage
To reproduce the analysis:
1. Install dependencies from `requirements.txt`.
2. Run `analysis.ipynb` or the corresponding Python script to load and process the data.
3. Adjust parameters or visualizations as needed for your own dataset.

## Visualization
This repository can include charts such as sales trends over time or side‑by‑side comparisons of promotional vs. non‑promotional periods. Adding images in an `images/` directory helps viewers quickly grasp the results.

## License
This project is licensed under the MIT License.
