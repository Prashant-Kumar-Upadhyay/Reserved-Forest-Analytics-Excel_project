## Overview
This project analyzes Reserved Forest Area (RFA) and Geographical Area (GA) data for states and union territories, providing insights into forest density, state contributions, and coverage ratios. It uses Excel to clean, calculate, and summarize metrics for easy reporting and analysis.

## Features
- **Detailed Analysis**: Calculates metrics like forest density, forest coverage, and ratios of reserved to protected forests.
- **Data Cleaning**: Handles inconsistencies like missing commas and alignment issues in numerical data.
- **Summarized Insights**: Aggregated views of forest data for comparisons and reporting.
- **Error Handling**: Ensures no calculation errors (e.g., handles zero denominators).

## Dataset Structure
1. **Table_1.2_RFAs_in_States_and_UT**: Raw data including GA, RFA, and forest type percentages.
2. **cleaning**: Cleaned dataset with formatted numbers and additional metrics.
3. **p1 to p5**: Summarized views of specific metrics like forest density and state contributions.
4. **report**: Placeholder for final outputs or summaries.

## Key Metrics
- **Forest Density**: Reserved Forest Area per 1,000 km² of Geographical Area.
- **Forest Coverage**: Percentage of GA covered by Reserved Forest Area.
- **State Contributions**: Percentage contribution to the national forest area.

## How to Use
1. **Prepare Data**: Ensure columns for GA and RFA are structured properly.
2. **Apply Calculations**: Use formulas like:
   ```excel
   =IF(B2=0, "", (A2/B2)*100)
   ```
3. **Format Numbers**: Use Excel’s “Format Cells” to add commas for large numbers.
4. **Review Summaries**: Use sheets like `p1` to `p5` for aggregated insights.

## Applications
- Analyzing forest conservation across states/UTs.
- Comparing forest density among regions.
- Reporting national and regional forest coverage trends.
