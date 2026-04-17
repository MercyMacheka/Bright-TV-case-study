BrightTV Viewership Analytics Case Study

Project Overview

The objective of this project is to assist the BrightTV Customer Value Management (CVM) team in meeting the CEO’s goal of growing the company’s subscription base for the current financial year
. By analysing user profiles and viewer transaction data, this project identifies consumption trends and provides strategic recommendations to foster audience growth and stimulate activity during low-usage periods
.
Data Description
The analysis is based on two primary datasets provided in the case study:
User Profiles: Demographic and account information for BrightTV subscribers
.
Viewer Transactions: Detailed session logs where each record represents a single viewing session for a subscriber
.
Technical Architecture & Workflow
The project follows a structured data pipeline to ensure accuracy and actionable insights:
Data Source: Microsoft excel file.
ETL Pipeline (Processing):
Time Standardisation: A critical technical requirement is the conversion of all dates and times from UTC to South African (SA) time to ensure alignment with local viewership patterns
.
Aggregation: Processing session-based records to identify high and low consumption periods
.
Storage: Processed data is stored and managed within Databricks for high-performance querying and analysis.
Analysis & Presentation: Insights are visualised through an interactive dashboard and an executive slide deck.
Key Analysis Areas
The project addresses four core areas requested by BrightTV leadership:
User & Usage Trends: Identifying how different segments interact with the platform
.
Consumption Factors: Analysing the drivers that influence when and why subscribers watch content
.
Low-Usage Strategy: Strategic content recommendations designed to increase engagement on days with typically lower consumption
.
Growth Initiatives: Recommended actions to further expand the overall BrightTV user base
.
Repository Deliverables
This repository contains the following assets developed for the CVM team presentation:
Interactive Dashboard (Infographic): A visual summary of trends and recommendations.
Data Flow & Architecture Diagram: A mapping of the data journey from source to Databricks.
20-Minute Executive Presentation: A slide deck structured for the CEO and CVM stakeholders.
Project Gantt Chart: A timeline tracking project progress from 1 April to 19 April 2026.
Project Timeline
The project was executed over a 19-day period (April 2026), covering data preparation, timezone conversion (UTC to SA time), analytical modelling, and final strategy formulation.
