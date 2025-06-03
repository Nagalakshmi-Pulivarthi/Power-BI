## Email Marketing Analysis -[Dashboard](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/Email%20Marketing_Viz.pdf)

This project is my first step into Power BI, applying concepts from my PL-300 exam preparation to analyze a random dataset from YouTube. I took an independent approach—enriching missing city/state data with Python, structuring age hierarchies, and creating KPIs for deeper insights. This hands-on experience strengthened my skills in data preparation, modeling, visualization, and interactivity, helping me build a portfolio that showcases my technical problem-solving abilities.

## Data Preparation
* The raw dataset contained missing values in the City and State columns, which were processed using [Python](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/scripts/City_generator.ipynb) to enhance geographic insights for analysis.

* Power Query was utilized to clean, transform, and structure the dataset, ensuring smooth integration into Power BI.

* [DAX](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/scripts/Power_Query/doc.txt) formulas were implemented to create key performance measures, including total enrollments per year, average age of enrollment, dynamic filters for marital status, and interactive KPI calculations for engagement trends.

## Key Features & Insights
1. Time-Based Analysis
Interactive Years Filter (2017–2020) for dynamic exploration.

[Total Enrollments over the years](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/EnroolmentsOver%20the%20years.PNG) visualization highlights yearly trends and growth.

2. Membership Status & Engagement
[Active vs. Non-Active](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/Marital.PNG) Members segmented by enrollment year.

    Enrollment behavior analyzed based on marital status, helping refine audience targeting.

3. Geographic Analysis
[Top 5 States & Cities](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/top%20statesand%20cities.PNG) by Enrollment provide a regional breakdown.

     Python-based data enrichment was used to fill missing city and state values, enhancing location-based insights.

4. Demographic & Behavioral Patterns
[Age Hierarchy](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/Age.PNG): Breakdown of enrollments by birth year and enrollment year.

5. [Peak Enrollment Time Slots](https://github.com/Nagalakshmi-Pulivarthi/Power-BI/blob/main/Email%20Marketing%20Analysis/Vizs/peaktime.PNG): Identifies optimal engagement periods for marketing campaigns.

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

### What’s Next?
Enhancing KPI measures for deeper engagement insights.

Expanding geographic analysis, if additional location data is available.

Exploring sentiment analysis for email campaign effectiveness (requires user interaction data).

Applying predictive analytics for enrollment trend forecasting (requires more historical and behavioral data).

📌 Currently, the dataset does not contain enough information for sentiment analysis, predictive modeling, or advanced geographic trends. However, if we introduce additional columns—such as user feedback, email interaction metrics, and extended historical data—we can unlock even richer insights for future analysis.

