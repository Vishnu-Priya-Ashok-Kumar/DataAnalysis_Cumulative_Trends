# DataAnalysis_Cumulative_Trends

# Table of Contents

1. [Project Overview](#Project-Overview)
2. [Deliverables](#Deliverables)
3. [Data Model](#Data_Model)
4. [Worksheets](#Worksheets)
5. [Usage](#Usage)
6. [Summary](#Summary)
7. [Contributors](#Contributors)

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

## Data Model

**Datamodel PD1**:
- Extracted checkout table from MS Access.
- Created columns:
  - ArriveHour: Extracted hour from the timearrive column.
  - WaitTimeOrder: Calculated wait time in minutes between TimeStartOrder and TimeArrive.
  - WaitRangeStart, WaitRangeTop, WaitRangePay: Utilized Vlookup function for range lookup.
  - WaitTimeTop: Calculated wait time in minutes between ActualStartTop and TimeStartTop.
  - WaitTimePay: Calculated wait time in minutes between ActualStartPay and TimeStartPay.
- TotalBought: Calculated as the sum of RegularBought, EconomyBought, and DeluxeBought.

## Worksheets

1. **Ranges**:
   - Created 14 ranges based on specified criteria.
   - Used for Vlookup formulas in the data model.
     
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/bcf5e902-ab16-41fc-b17c-1f5b379b02cd)

2. **Frequencies**:
   - Contains pivot tables for frequency analysis of wait times.
   - Indicates most wait times are less than 0.25.
     
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/0423736b-3e69-4c77-9ee8-e02b8abf68ca)
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/6785a089-9771-4e5f-9df9-8362e5b11d62)

3. **Correlations**:
   - Contains correlation analysis results for different wait time types.
   - Subsheets:
     - CR- AA, CR- SK, CR- VP: Individual correlation analyses by group members.
       
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/f717eb3f-3ed7-491e-b700-c36b8c46000c)

4. **Cumulative-**:
   - Contains cumulative analysis data and models.
   - Subsheets:
     - Cmltv DM: Data model for cumulative analysis.
       
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/b3180c51-a4d3-4ace-ac89-4c35b0b41d8c)

 -
     - C Analysis: Analysis of cumulative data.
     
![image](https://github.com/priya-ak/DataAnalysis_Cumulative_Trends/assets/67804361/1daf8c80-4c1a-4ffc-b429-88fc60ed1e02)


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

## Summary

This project involves extensive data analysis including correlation, range grouping, and linear regression. The data model (Datamodel PD1) serves as the foundation for various analyses. Worksheets such as Ranges, Frequencies, and Correlations provide detailed insights into wait times and their correlations. The project culminates in cumulative analysis to understand trends over time. Each analysis is documented thoroughly to ensure reproducibility and clarity.

### Contributors
- Initials: AA, SK, VP
- Team: 8145W23-S1-PD
