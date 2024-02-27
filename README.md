# DataAnalysis_Cumulative_Trends

# Table of Contents

1. [Project Overview](#project-overview)
2. [Deliverables](#deliverables)
3. [Usage](#usage)
4. [Summary](#summary)
5. [Contributors](#contributors)

This table of contents outlines the sections and subsections of the README for easy navigation.
## Project Overview
This repository contains the deliverables and documentation for a data analysis project conducted by Team-8145W23-S1-PD. The project involved analyzing wait times and order frequencies to optimize processes within a checkout system. Comprehensive data analysis project exploring correlations, frequency distributions, and cumulative trends. Excel-based workflows with documentation. Team collaboration. Deliverables include detailed analysis and data models.

## Deliverables
   1. **Practical D - ReadMeFirst sheet**: Initial project documentation.
   2. **Workflows Workbook**: Documentation of analysis workflows.
   3. **Correlation Analysis Workflow**: Steps for correlation analysis.
   4. **Range Grouping Analysis Workflow**: Steps for range grouping analysis.
   5. **Linear Regression Analysis Workflow**: Steps for linear regression analysis.
	6. **Data Model PD1**: Excel sheet with data model and calculations.
	7. **Ranges**: Excel sheet with wait time ranges.
	8. **Frequencies**: Excel sheet with wait time frequency analysis.
	9. **Correlations**: Excel sheets (CR-AA, CR-SK, CR-VP) with correlation analysis results.
	10. **Cumulative-**: Excel sheets (Cmltv DM, C Analysis) with cumulative analysis.

### Data Model

**Datamodel PD1**:
- Extracted checkout table from MS Access.
- Created columns:
  - ArriveHour: Extracted hour from the timearrive column.
  - WaitTimeOrder: Calculated wait time in minutes between TimeStartOrder and TimeArrive.
  - WaitRangeStart, WaitRangeTop, WaitRangePay: Utilized Vlookup function for range lookup.
  - WaitTimeTop: Calculated wait time in minutes between ActualStartTop and TimeStartTop.
  - WaitTimePay: Calculated wait time in minutes between ActualStartPay and TimeStartPay.
- TotalBought: Calculated as the sum of RegularBought, EconomyBought, and DeluxeBought.

### Worksheets

1. **Ranges**:
   - Created 14 ranges based on specified criteria.
   - Used for Vlookup formulas in the data model.

2. **Frequencies**:
   - Contains pivot tables for frequency analysis of wait times.
   - Indicates most wait times are less than 0.25.

3. **Correlations**:
   - Contains correlation analysis results for different wait time types.
   - Subsheets:
     - CR- AA, CR- SK, CR- VP: Individual correlation analyses by group members.

4. **Cumulative-**:
   - Contains cumulative analysis data and models.
   - Subsheets:
     - Cmltv DM: Data model for cumulative analysis.
     - C Analysis: Analysis of cumulative data.


## Usage

1. **Data Model PD1**
   - Extract the checkout data from MS Access.
   - Calculate wait times using formulas for various stages of the checkout process.
   - Utilize VLOOKUP function from Ranges worksheet to categorize wait times.
   - Calculate TotalBought by summing up different types of orders.

2. **Ranges**
   - Create different ranges for wait times as per requirements.
   - Use filters to obtain min and max values for wait times.

3. **Frequencies**
   - Create pivot tables to analyze the count of wait times for different stages of checkout.
   - Identify patterns in wait time distributions.

4. **Correlations (CR-AA, CR-SK, CR-VP)**
   - Duplicate wait time data from Frequencies sheet.
   - Sort and filter data to remove zero values.
   - Conduct correlation analysis between arrival hour and wait times.
   - Generate scattergrams to visualize correlations.

5. **Cumulative- (Cmltv DM, C Analysis)**
   - Create pivot tables for cumulative analysis of total orders.
   - Clean and adjust pivot table data.
   - Generate scattergrams and perform linear regression analysis to understand trends in total orders over time.

### Summary

This project involves extensive data analysis including correlation, range grouping, and linear regression. The data model (Datamodel PD1) serves as the foundation for various analyses. Worksheets such as Ranges, Frequencies, and Correlations provide detailed insights into wait times and their correlations. The project culminates in cumulative analysis to understand trends over time. Each analysis is documented thoroughly to ensure reproducibility and clarity.

### Contributors
- Initials: AA, SK, VP
- Team: 8145W23-S1-PD
