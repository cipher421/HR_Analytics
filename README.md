# HR Analytics Dashboard

This repository contains an HR analytics project focused on employee attrition analysis. The project uses a structured employee dataset and visualizes key workforce trends through a Power BI dashboard.

## Overview

The dashboard highlights patterns related to:

- employee count and attrition rate
- age-based attrition trends
- department-wise workforce distribution
- job role and salary level impact on attrition
- education field mix and employee experience factors

The project is designed to help HR teams identify risk areas and understand which employee segments are more likely to leave the organization.

## Project Files

- [Dataset/HR_Analytics.csv](Dataset/HR_Analytics.csv) — raw employee dataset used for analysis
- [HR_Analytics.pbix](HR_Analytics.pbix) — Power BI report file
- [HR_Analytics.pdf](HR_Analytics.pdf) — exported PDF version of the dashboard
- [HR_Analystics.png](HR_Analystics.png) — dashboard preview screenshot

## Dataset Summary

The dataset contains employee-level records with attributes such as:

- demographic information: Age, Gender, MaritalStatus
- employment details: Department, JobRole, JobLevel, YearsAtCompany
- compensation: MonthlyIncome, SalarySlab, DailyRate, MonthlyRate
- employee experience: TotalWorkingYears, YearsInCurrentRole, YearsSinceLastPromotion
- people metrics: Attrition, OverTime, TrainingTimesLastYear, WorkLifeBalance
- environment factors: DistanceFromHome, BusinessTravel, EnvironmentSatisfaction

These fields allow the dashboard to assess how attrition varies by age, education, salary band, role, and time with the company.

## Dashboard Highlights

From the dashboard preview, the key business metrics include:

- Total Employees: 1,470
- Attrition: 237
- Attrition Rate: 16.1%
- Average Age: 37 years
- Monthly Income: 7K
- Average Years at Company: 7 years

The visuals also show:

- attrition by age group
- attrition by year of employment
- education distribution
- attrition by job role
- attrition by salary band

## How to Use

1. Open the dataset in [Dataset/HR_Analytics.csv](Dataset/HR_Analytics.csv) to review the employee records.
2. Open [HR_Analytics.pbix](HR_Analytics.pbix) in Power BI Desktop to interact with the dashboard.
3. Use [HR_Analytics.pdf](HR_Analytics.pdf) or [HR_Analystics.png](HR_Analystics.png) for a quick visual snapshot without opening Power BI.

## Business Value

This analysis can support:

- employee retention planning
- department-specific HR interventions
- hiring and workforce balancing decisions
- identifying attrition hotspots by role and salary level

## Tools Used

- Microsoft Power BI
- CSV data source
- Data visualization and dashboard reporting

## Notes

This repository does not contain a traditional application codebase or web app; it is a data analytics project built around HR attrition insights and dashboard reporting.