# Project: Resources Allocation with Demand/Supply Gap Analysis
## Objective:
The goal of this analysis was to identify gaps between Contracted Hours, Allocated Hours, and
Remaining for each employee in every region. The insights gained from this gap analysis would
help optimize resource allocation and improve efficiency in each region.

## Analysis Approach:
The analysis conducted in this project used Time-Series Analysis to identify the gap between three
features: *Contracted Hours*, *Allocated Hours*, and *Remaining*, over a given time period. This type of
analysis is commonly referred to as Gap Analysis.

## Project Analysis Steps:
- Created a separate DataFrame for each region.
- Performed data validation and cleansing, which included:
  * Reshaping the data to add emp_id in a separate column to correspond with each month and (Contracted Hours, Allocated Hours, and Remaining).
  * Validating the values of Remaining for each employee in each month by manually calculating it and comparing it with the original Remaining values in each region.
  * Handling duplicate values.
  * Handling null values.
- Conducted data analysis by aggregating Contracted Hours, Allocated Hours, and Remaining over date using the mean.
- Plotted the aggregated values.
- Extracted findings from the analysis.
- Identified data-driven actionable business decisions based on the findings.

------------
*Full Project can be accessed through this link:* [Supply_And_Demand_Gap_Analysis.ipynb](https://github.com/mustafaa7med/Supply-and-Demand-Gap-Analysis/blob/main/Supply_And_Demand_Gap_Analysis.ipynb)
