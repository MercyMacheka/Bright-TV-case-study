# Bright-TV-case-study
This repository contains my analysis of BrightTV’s user profiles and viewership data. The objective of the case study is to provide actionable insights to help BrightTV’s CEO and Customer Value Management (CVM) team grow the company’s subscription base during the current financial year.

Objectives
Analyze user and usage trends (who is watching, when, and how).

Identify factors influencing consumption (content type, device, demographics).

Recommend content strategies to increase consumption on low‑usage days.

Suggest initiatives to grow BrightTV’s user base (acquisition, retention, engagement).
 Dataset
Two datasets were used:

Bright_TV_User_Profiles.xlsx – demographic and subscription details of users.

Bright_TV_Viewership.xlsx – session‑level viewing transactions (UTC timestamps, channel, duration).

Note: All timestamps were converted from UTC to South Africa Standard Time (UTC+2) for accurate local insights.
 Methodology
SQL Queries:

Full outer joins to combine user profiles with viewership sessions.

Aggregations to analyze daily/weekly/hourly trends.

Case statements to categorize users by age, gender, and time buckets.

Conversion functions (from_utc_timestamp) to localize time.

Visualization:

Tableau dashboards for trends (line charts, heatmaps, bar charts).

Demographic breakdowns and content consumption patterns.

 Key Insights
Peak viewing occurs in the evenings (18:00–22:00) and on weekends.

Young adults (18–30) are the most engaged demographic.

Drama and sports content drive longer session durations.

Mobile devices are increasingly used for short‑form content.

 Recommendations
Content Strategy: Introduce midweek premieres, themed nights, and short‑form content for weekdays.

Growth Initiatives: Launch referral programs, bundle subscriptions with ISPs, and offer tiered pricing.

Retention: Personalized recommendations and targeted campaigns for inactive users.

 Deliverables
SQL scripts for data preparation and analysis.

Tableau dashboards for visualization.

Presentation slides summarizing insights and recommendations.
