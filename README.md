# Employee Attrition Analysis Dashboard

An interactive Excel workbook analyzing workforce attrition patterns across 1,470 employees 
to identify which departments and salary levels drive the highest turnover.

## Project Overview

This project uses the IBM HR Analytics dataset to answer one business question: 
**where is attrition concentrated, and who is most likely to leave next?**

The workbook is structured across four sheets — raw data, a lookup table of model 
assumptions, an analysis layer with calculated metrics, and an executive dashboard.

## Key Features

- **Attrition segmentation** using COUNTIFS across department, salary band, and age group
- **Flight risk scoring model** that flags current employees as High / Medium / Low risk 
  based on four data-validated factors: overtime, job satisfaction, environment satisfaction, work life balance
- **Assumptions** via VLOOKUP-driven lookup tables — weights and thresholds 
  are documented in one place and referenced dynamically by all formulas
- **Interactive dashboard** with slicer-driven charts, KPI cards, and a written insight summary

## Tools & Skills Demonstrated

- Microsoft Excel — COUNTIFS, VLOOKUP, INDEX/MATCH, IFS, nested IF logic
- PivotTables and slicers
- Conditional formatting

## Key Finding

HR employees in the salary band 46-60 and 61-75 have the highest attrition rate of 33%. Across departments, Sales has the highest attrition rate and across salary bands, 46-60 has the highest attrition rate. In total 16% of employees were characterised as Medium or High Risk. 

## Dataset

IBM HR Analytics Employee Attrition & Performance — publicly available on Kaggle  
1,470 employee records, 35 original variables, 14 used in this analysis

## File Structure

| Sheet | Purpose |
|---|---|
| `Raw_Data` | Original dataset — untouched source |
| `Lookup_Tables` | Risk score weights and salary band thresholds |
| `Analysis` | Calculated columns, summary tables, flight risk scores |
| `PivotTable1` | Summarised attrition counts across department and salary bands |
| `PivotTable2` | Summarised flight risk scores |
| `Dashboard` | Interactive slicer-driven executive summary |
