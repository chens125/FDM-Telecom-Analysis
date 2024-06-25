# FDM Mobile Analysis

## Overview

This project analyzes the high sales performance of the mobile market from October to December 2019, focusing on networks, handsets, SIMO plans, and specific activities such as price drops and promotions.

## Objective

Identify which networks, handsets, SIMO plans, and specific activities (e.g., price drops & promotions) drove the high sales performance during the specified period.

## Data Sources

1. **Sales Performance Data**: Weekly sales volumes for the total market, split by price bracket. This data helps highlight key weeks for analysis.
2. **Pricing & Offer Data**: Daily and weekly tariffs from networks for SIMO and handset plans, with over 40 KPIs including "Headline Monthly Cost," "Data Allowance," and "Promotion."

## Analysis Process

1. **Data Observation & Data Cleaning**:
   - Converted serial dates to datetime format.
   - Extracted the month from the 'Date' column.
   - Filled missing values in the 'On Promotion' column and converted it to binary format (1 for Yes, 0 for No).

2. **Insights from Sales Performance**:
   - Identified key sales spikes in November (handset sales driven by Black Friday promotions) and early January (SIMO plans driven by Boxing Day/New Year promotions).

3. **Insights Combination**:
   - Analyzed the proportion of promoted products over time.
   - Examined network-specific promotion strategies.
   - Investigated PAYM price ranges and their impact on sales during the Black Friday period.
   - Looked into device-specific promotion levels, particularly focusing on high-performing devices like Galaxy S10 and iPhone XR (64GB).

4. **Reporting**:
   - Created a PowerPoint presentation summarizing the findings, including charts and key takeaways.

## Key Findings

- **November Sales Spike**: Driven by handset sales in the 30-39.9 cost range, influenced by Black Friday promotions.
- **Early January Sales Recovery**: Driven by SIMO plans in the 0-9.9 cost range, influenced by Boxing Day/New Year promotions.
- **Promotion Trends**: Significant increase in promoted products from mid-November leading to Black Friday.
- **Network Strategies**: Varying promotion strategies across networks, with BT maintaining high promotion levels and Giffgaff significantly increasing during sales periods.
- **PAYM Pricing**: High headline MLR promo % for PAYM products in the 20-29.9 and 30-39.9 price ranges during Black Friday.
- **Device Promotions**: High promotion levels for Galaxy S10 and iPhone XR (64GB) during the Black Friday period.

## Recommendations

- Maintain robust promotions during key sales periods like Black Friday and Boxing Day/New Year.
- Tailor promotional strategies to specific devices and customer segments for maximum impact.

## Files in the Repository

- `FDM_Mobile_Analysis_Presentation.pptx`: PowerPoint presentation with analysis findings.
- `Task 1_Pricing & Offer Data.csv`: Raw data file used for analysis.
- `Siyu_task.ipynb`: Jupyter Notebook with code for data cleaning, analysis, and visualization.

## How to Run the Analysis

1. **Install Required Libraries**:
   ```sh
   pip install pandas matplotlib seaborn nbformat

"# FDM-Telecom-Analysis" 
