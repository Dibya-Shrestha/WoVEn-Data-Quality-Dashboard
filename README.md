📘 WoVEn Dashboard – README & User Guide
🧭 Purpose

This dashboard visualises workforce data quality trends using WoVEn (Workforce Validation Engine) score summary reports. It supports NHS organisations in identifying, tracking, and improving ESR (Electronic Staff Record) data integrity over time.

📥 Data Sources
- Monthly WoVEn Score Summary Excel files (Jan 2024 – Jul 2024)
- GuidanceWoVEnReports_V7.4.pdf – Official documentation

🧱 How the Data Table Was Generated

1️. Monthly File Preparation

2. Merged All Monthly Sheets
   
3. Added column like MonthNumber, Quartile Value, PreviousQuartile, Previous Quartile Value and Trend

Dashboard Components

🔢 Top Panel
Total Organisation: Displays the number of unique NHS organisations analysed across all months.
Note Box: Reminder that WoVEn scores are diagnostic indicators, not comparative rankings.
Month Selector: Interactive filter to slice data by month (Jan to Jul).

📈 Charts Explained

📉 Benchmark Group Distribution (Top Quartile)

What It Shows: Monthly count of organisations in the Top Quartile, grouped by benchmark type (e.g., Acute-Large, Integrated Care).

Purpose: Understand which types of organisations consistently maintain high data quality.

🍩 Total Records Submitted (VPDs)

What It Shows: Donut chart displaying VPD submission volumes.

Purpose: Visualise data workload volume contributing to scoring.

🏆 High Performing Organisations Based on VPD Score

What It Shows: Organisations with the highest average WoVEn scores (calculated or derived from known quartile boundaries).

Purpose: Identify consistently top-performing organisations for benchmarking.

📊 Average VPD Count by Quartile

What It Shows: Bar chart comparing average VPD submissions for each quartile.

Purpose: Explore whether high data volume correlates with better/worse quartile placement.

🧱 Monthly Quartile Composition

What It Shows: Distribution of organisations across quartiles per month.

Purpose: Track changes in data quality standing at a glance.

🔄 Monthly Performance Movement Trends (by Region)

What It Shows: Percentage of organisations in each region that improved, dropped, or remained in the same quartile month-to-month.

Purpose: Understand regional trends and performance stability.

🔍 Key Metrics & Insights
Metric	Explanation
- Quartile	Indicates an organisation’s relative data quality. Top = Highest; Fourth = Lowest
- VPDs	Validation Performance Data = record volume used in validations
- Trend	Derived movement based on previous month's quartile (Improved, Dropped, Same)
- Benchmark Group	Classification of organisations by size/type (e.g., Acute-Large)
- Region	NHS Region where the organisation operates
