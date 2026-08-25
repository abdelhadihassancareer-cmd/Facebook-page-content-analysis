# Facebook-page-content-analysis
Three-month Facebook Page performance analysis using Power BI, covering data cleaning, transformation, KPI analysis, trend analysis, and interactive dashboard development.
Facebook Page Content Analysis — Power BI
📊 Project Overview

This project analyzes the performance of a Facebook Page over a three-month period using Microsoft Power BI.

The project focuses on transforming and preparing raw Facebook performance data into a structured dataset, then building an interactive dashboard to monitor key performance indicators, audience activity, content consumption, and engagement trends.

Note: The underlying dataset belongs to a company and cannot be publicly shared due to confidentiality restrictions. Therefore, the raw data and the .pbix file is intentionally excluded from this repository.

🎯 Objectives

The main objectives of this project were to:

Consolidate Facebook performance data from multiple sources.
Clean and organize the dataset for analysis.
Review and handle missing values.
Prepare and standardize analytical fields.
Apply appropriate aggregations to performance metrics.
Analyze performance trends over time.
Build a clear and management-friendly Power BI dashboard.
Identify notable performance patterns and areas that may require further investigation.
🛠️ Tools & Technologies
Power BI Desktop — Data modeling, analysis, and dashboard development
Power Query — Data preparation and transformation
CSV — Source data organization and preparation
DAX — Measures and analytical calculations where required
🔄 Data Preparation Process

The data preparation workflow consisted of the following steps:

1. Data Consolidation

Relevant Facebook performance data was combined into a unified analytical dataset.

The main Power BI table used in the report is:

Facebook Content Unified Data

2. Data Cleaning

The dataset was reviewed for:

Missing values
Inconsistent data types
Date fields
Numeric performance fields
Column structure and naming
3. Data Transformation

The required fields were prepared and standardized so they could be used consistently within Power BI.

4. Aggregation

Performance metrics were aggregated according to their intended use in the dashboard.

The current dashboard uses SUM aggregations for the displayed KPI and chart metrics.

📈 Dashboard

The dashboard provides an overview of the Facebook Page's performance through KPI cards and visual trend analysis.

Key KPIs
Metric	Dashboard Value
Reactions	143K
Profile Visits	135K
Followers	77K
Link Clicks	80
Views	~5.9M
Viewers	~3.8M
Main Visualizations
Reactions & Profile Visits

A daily trend chart is used to compare reactions and profile visits throughout the analysis period.

This helps identify:

Performance spikes
Periods of increased audience activity
Changes in engagement over time
Dates that may require further content-level investigation
Views & Viewers

A comparison of total views and viewers provides an overview of content consumption during the analysis period.

🔎 Key Insights

The dashboard highlights several important observations:

The Page generated a high volume of content views during the analyzed period.
Reactions and profile visits experienced noticeable spikes on specific dates.
Performance was not evenly distributed throughout the period, suggesting that certain publishing dates or content types may have contributed disproportionately to overall activity.
Link clicks were relatively low compared with the volume of views and other engagement metrics.
Further post-level analysis would help determine which content formats, topics, or publishing times contributed to the strongest performance.
💡 Recommended Next Steps

Future analysis could extend the dashboard by adding:

Content type analysis
Post-level performance
Engagement rate
Click-through rate
Performance by publishing time
Performance by content topic
Top-performing posts
Monthly performance comparison
Interactive date and content-type filters

These additions would make it possible to move from descriptive performance reporting toward deeper content-performance analysis.

⚠️ Data Considerations

Some Facebook metrics require careful interpretation depending on how they are provided in the original export.

For example, if Followers or Viewers represent daily snapshots rather than incremental daily activity, summing the values across multiple days may overstate the actual period-level figure.

Therefore, metric definitions should be validated against the original Facebook reporting definitions before using cumulative audience metrics as formal business KPIs.

🔐 Confidentiality

The raw Facebook Page data used in this project is company-owned and cannot be publicly distributed.

For this reason:

Raw datasets are not included.
Confidential business information is not published.
Only non-sensitive dashboard visuals and project documentation are shared.
The project demonstrates the analytical methodology without exposing the underlying company data.

👤 Project Focus:
This project demonstrates practical skills in:

Data cleaning
Data transformation
Data consolidation
Data analysis
Power BI
Power Query
Dashboard design
KPI development
Trend analysis
Business-oriented data visualization
📄 Project Documentation

A detailed project report is included in the docs. It provides additional information about the data preparation process, aggregation approach, dashboard design, analytical findings, and recommendations.
