# Business Data Cleaning, Validation & Excel Reporting

## Problem Summary

This project cleans and validates retail order data to prepare it for business reporting.

## Dataset Description

The dataset contains customer, product, order, shipping, sales, profit, payment, and order status information.

## Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Formulas

## Cleaning Steps

- Standardized text fields
- Cleaned Region and Ship Mode
- Validated dates
- Created calculated columns
- Applied business rules
- Built pivot reports

## Business Rules

- Missing Region → Unknown
- Missing Ship Mode → Unknown
- Missing Discount → 0
- Cancelled orders excluded
- Failed payments excluded
- Refunded orders summarized

## Data Quality Summary

The dataset was reviewed for missing values, duplicate records, invalid discounts, and date issues.

## Pivot Reports

- Sales by Region
- Sales by Category
- Orders by Ship Mode
- Profit Margin by Segment
- Refund Analysis
- Monthly Sales Trend

## Key Business Insights

- Regional sales vary significantly.
- Some categories generate higher profit.
- Shipping mode impacts order volume.
- Refunds should be monitored separately.

## Assumptions

Blank discounts were treated as zero.

## Limitations

Mixed date formats required manual review.

## Screenshots Included

- raw_data_preview.png
- cleaned_data_preview.png
- pivot_summary_1.png
- pivot_summary_2.png
