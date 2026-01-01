# Emergency Department Wait Time Analysis

## Overview
This project analyzes emergency department (ED) wait times and length of stay (LOS) across hospitals to better understand operational efficiency and patient flow. Using hospital-level visit data, time-based trends, and comparative metrics, the analysis identifies patterns that contribute to longer wait times and highlights areas where operational improvements may reduce patient delays.

## Motivation
Emergency department crowding and prolonged wait times directly affect patient outcomes, staff workload, and overall hospital performance. Drawing on prior experience working in a high-volume emergency medical services environment, this project approaches ED wait times from both a data-driven and operational perspective, focusing on how system-level factors influence patient throughput rather than demand alone.

## Key Questions
- How does emergency department visit volume relate to average length of stay?
- Which hospitals consistently demonstrate higher or lower operational efficiency?
- Are higher wait times driven primarily by demand, or by hospital-specific processes?
- How do wait times and visit patterns change over time?

## Data Sources
- Massachusetts Center for Health Information and Analysis (CHIA)

## Methods
- Data cleaning and validation using Python
- Exploratory data analysis (EDA)
- Hospital-level comparisons using normalized efficiency metrics
- Time-series trend analysis

## Key Findings
- High emergency department visit volume alone does not fully explain longer wait times.
- Some hospitals maintain relatively low LOS despite consistently high patient volume, suggesting stronger operational efficiency.
- Variability in wait times across hospitals points to differences in internal processes rather than regional demand alone.

## Limitations
- Analysis is limited to available reported metrics and does not capture real-time staffing or bed availability.
- External factors such as case severity and seasonal illness patterns are not fully observable in the dataset.
