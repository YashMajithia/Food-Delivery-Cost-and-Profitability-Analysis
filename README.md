# Food-Delivery-Cost-and-Profitability-Analysis

## Overview
This project analyzes food delivery data to gain insights into cost structures, discount patterns, and profitability. The analysis includes processing timestamps, extracting discount information, and calculating discount impact on order values. The goal is to improve data-driven decision-making in food delivery operations.

## Dataset
The dataset contains the following key columns:
- Order Date and Time: Timestamp of when the order was placed.
- Delivery Date and Time: Timestamp of when the order was delivered.
- Order Value: Total cost of the order before discounts.
- Discounts and Offers: Text descriptions of discounts applied (e.g., '20% off' or '50 off').
- Other Attributes: Various metadata related to orders and deliveries.

## Methodology
1. Data Cleaning and Pre-Processing
- Converted date and time columns into `datetime` format for analysis.
- Handled missing or non-standard values in the "Discounts and Offers" column.
2. Discount Extraction and Calculation
- Extracted numerical discount values from text-based discount descriptions.
- Differentiated between percentage-based and fixed-amount discounts.
- Calculated the final discount amount applied to each order.
3. Analysis & Insights
- Investigated discount trends and their impact on profitability.
- Identified patterns in order values, delivery times, and discount usage.

## Key Findings
- **High Discount Dependency**: A significant number of orders rely on heavy discounts, reducing net profitability.
- **Percentage Discounts vs. Fixed Discounts**: Percentage-based discounts tend to have a higher impact on revenue loss than fixed-amount discounts.
- **Order Values vs Discounts**: Higher-order values often correlate with higher discount percentages.
- **Delivery Timelines**: Orders with significant discounts sometimes exhibit longer delivery times, possibly due to high demand.

## Technologies Used
- Python: Data processing and analysis
- Pandas: Data manipulation
- Matplotlib/Seaborn: Visualization (if applicable)
- Jupyter Notebook: Code execution and analysis

## How to run the project
1. Install dependencies:
`pip install pandas matplotlib seaborn`
2. Open the Jupyter notebook:
`jupyter notebook`
3. Run the notebook step by step to reproduce the analysis.

## Future Scope
- Incorporate predictive modeling to forecast discount impact
- Optimize discount strategies to balance profitability and customer retention
- Expand analysis to include delivery partner performance and operational costs
