# Facebook Business Activity Trends Analysis

## Overview

This project analyzes the global business impact of COVID-19, particularly focusing on its varying effects on small businesses. The analysis leverages Facebook data and the Activity Quantile metric to measure the level of business activity relative to a baseline period. The objective is to provide actionable insights for businesses, analysts, and policymakers.

## Objectives

- Analyze the global business impact of COVID-19 using Facebook business activity data.
- Provide insights into how small businesses have been affected during the pandemic.
- Utilize the Activity Quantile metric with an anomaly threshold of 0.5 to detect changes in business activity.

## Key Metrics

- **Activity Quantile Metric**: Measures the level of activity relative to a baseline period, with a threshold set at 0.5 to detect anomalies.
- **Activity Percentage**: A 7-day rolling sum of total activity as a percent of the average weekly baseline. This metric is influenced by outliers and is used to understand business activity trends over time.

## Methodology

1. **Baseline Period Selection**: Identifying a suitable baseline period to compare business activity levels during and after the onset of COVID-19.
2. **Removal of Long-Term Trends**: Adjusting data to remove long-term trends, ensuring that the focus is on short-term changes due to the pandemic.
3. **Activity Quantile Metric**: Applying the Activity Quantile metric to gauge the relative level of business activity.
4. **Downtime Detection**: Identifying periods of significant drop in business activity, which may indicate economic downturns or disruptions.

## Insights Provided

- The dataset provides insights into the incomplete economic toll of COVID-19 on businesses.
- Highlights regional and sector variations in business impact.
- Uses a fixed cohort approach for consistent analysis across different periods.
- Emphasizes the importance of sensitivity in interpreting the results.

## Limitations

- The dataset lacks information on continent-wise impact.
- There is no detailed analysis of the impact on specific business verticals.
- Lacks insights into the differences between weekend and weekday business activity.
- Does not specify the high-impact countries where businesses were most affected.

## Contact

For more information or collaboration, please reach out to:

**[Namia]**  
Email: [nami29221@gmail.com](mailto:nami29221@gmail.com)

