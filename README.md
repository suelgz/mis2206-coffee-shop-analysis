# Coffee Sales Revenue Analysis

## Purpose
Analyze coffee shop sales data to understand hourly revenue patterns and identify improvement opportunities.

## Problem
- Revenue is uneven during the day
- Morning hours generate most income
- Early morning and late evening show low performance
- Possible inefficiency in staff and resource allocation

## Data Processing
- Converted `datetime` to proper datetime format
- Created `hour_of_day` variable
- Checked for missing values (none found)
- Checked for invalid/negative revenue transactions (none found)

## Analysis
- Aggregated revenue by hour
- Visualized hourly revenue distribution
- Examined revenue variability using a boxplot

## Key Findings
- Peak revenue hours: **8 AM – 12 PM**
- Highest revenue hour: **10 AM**
- Off-peak hours underperform
- Revenue differences are mainly driven by **customer volume**

## Recommendations
- Align staff scheduling with peak hours
- Introduce promotions during low-demand hours
- Increase transaction value during peak times (premium/add-ons)
- Monitor hourly trends regularly

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

  ## Author
  Su Elagöz
