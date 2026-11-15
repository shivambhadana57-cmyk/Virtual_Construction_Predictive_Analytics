
# Data

## Overview

This folder contains information about the datasets used in the Virtual Construction Predictive Analytics project.

Three CSV datasets were used for project performance monitoring, EVM analysis, and project risk assessment.

## Datasets Used

### 1. project_risk_raw_dataset.csv

Contains project characteristics and risk-related information.

Main fields include:
- Project_ID
- Project_Type
- Project_Budget_USD
- Complexity_Score
- Priority_Level
- Risk_Level
- Project_Phase
- Team_Size

### 2. simulated_project_ev_metrics_final.csv

Contains monthly Earned Value Management (EVM) information.

Main fields include:
- Project_ID
- Month
- PV (Planned Value)
- EV (Earned Value)
- AC (Actual Cost)
- CPI_Cumulative
- SPI_Cumulative
- Planned_Budget

### 3. project_delay_cost_overrun_summary_final.csv

Contains project-level cost and schedule outcomes.

Main fields include:
- Project_ID
- Estimated_Timeline_Months
- Actual_Duration_Months
- Planned_Budget
- Actual_Cost
- Schedule_Delay
- Cost_Overrun

## Data Source

Mendeley Data:

https://data.mendeley.com/datasets/2p5sz57wh2/1

## Data Preparation

The CSV files were imported into Power BI Desktop. Column headers, delimiters, and data types were checked in Power Query before creating the data model.

The EVM dataset contains multiple monthly records for each project. Repeated Project_ID values in this dataset are therefore expected.

## Note

The datasets contain simulated information. Refer to the original source for dataset licensing and attribution details.
