
# Power BI Dashboard

## Overview

This folder contains the Microsoft Power BI dashboard developed for the Virtual Construction Predictive Analytics project.

The dashboard combines project performance monitoring, EVM-based forecasting, and project risk analysis.

## Dashboard Pages

### Page 1: Project Performance & Risk Overview

Includes:
- Total Projects
- Total Planned Budget
- Total Actual Cost
- Total Cost Overrun
- Cost Overrun by Project Type
- Project Distribution by Risk Level
- Average Schedule Delay by Project Type

### Page 2: Predictive Cost & Schedule Analysis

Includes:
- Forecast Final Cost (EAC)
- Forecast Cost Overrun
- Forecast Project Duration
- Forecast Schedule Delay
- Latest Cumulative CPI
- Latest Cumulative SPI
- Monthly PV, EV, and AC
- Cumulative CPI and SPI
- Forecast Cost Overrun by Project

### Page 3: Project Risk & Complexity Analysis

Includes:
- Risk Distribution
- Projects by Project Type
- Project Complexity vs Budget by Risk Level

### Page 4: Project Filters & Controls

Includes four synchronised slicers:
- Project Type
- Risk Level
- Project ID
- Priority Level

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX

## Data Model

The datasets are connected using Project_ID.

The project risk dataset is related to the project-level cost and schedule summary and the monthly EVM dataset.

## Forecasting Method

The project uses cumulative CPI and SPI to calculate EVM-based cost and duration forecasts.

These calculations are formula-based projections, not trained machine-learning predictions.

## How to Open

Open the `.pbix` file using Microsoft Power BI Desktop.

The original datasets can be obtained from the Mendeley Data source linked in the data folder README.
