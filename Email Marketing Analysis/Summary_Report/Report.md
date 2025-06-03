# Email Marketing Analysis 

This Power BI dashboard provides a comprehensive analysis of email marketing enrollments from 2017 to 2020, offering insights into enrollment trends, member activity, demographics, and geographic distributions. The dashboard integrates interactive filtering and dynamic visualizations to support data-driven marketing strategies.

## Data Preparation
The raw dataset contained missing values in the City and State columns, which were processed using Python to enhance geographic insights for analysis.

Power Query was utilized to clean, transform, and structure the dataset, ensuring smooth integration into Power BI.

DAX formulas were implemented to create key performance measures, including total enrollments per year, average age of enrollment, dynamic filters for marital status, and interactive KPI calculations for engagement trends.

## Key Features & Insights
1. Time-Based Analysis
Interactive Years Filter (2017–2020) for dynamic exploration.

Total Enrollment Per Year visualization highlights yearly trends and growth.

2. Membership Status & Engagement
Active vs. Non-Active Members segmented by enrollment year.

Enrollment behavior analyzed based on marital status, helping refine audience targeting.

3. Geographic Analysis
Top 5 States & Cities by Enrollment provide a regional breakdown.

Python-based data enrichment was used to fill missing city and state values, enhancing location-based insights.

4. Demographic & Behavioral Patterns
Age Hierarchy: Breakdown of enrollments by birth year and enrollment year.

Peak Enrollment Time Slots: Identifies optimal engagement periods for marketing campaigns.

## Interactivity & Dashboard Functionality
All visualizations are fully interactive, dynamically responding to the Years Filter selection.

Users can explore enrollment patterns across different age groups, locations, engagement statuses, and marital statuses.

## Key Takeaways
Peak Enrollment Year: 2018 recorded the highest enrollment count (5,040 enrollments).

Lowest Enrollment Year: 2017, the first year of data collection, had the lowest enrollment numbers, likely due to initial adoption and awareness.

Average Age of Enrollment: Captures key demographic trends, helping refine marketing strategies.

Gender Distribution: Male enrollments consistently surpass female enrollments across all years.

Enrollment Trends by Household Type:

2017: Singles had the highest enrollment numbers.

2018 onward: Couples with children became the most active and engaged group interacting with emails and advertisements.

Activity by Marital Status: Married individuals with children are significantly more active compared to unmarried individuals or those without children, showing a higher response rate to email marketing efforts.

## What we can do a more research with the extra columns/data 
Refine KPI measures for deeper insights into engagement trends.

Integrate sentiment analysis to evaluate responses to email campaigns.

Apply predictive analytics to forecast future enrollment trends.

