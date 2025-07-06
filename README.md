# Customer_journey_optimization
This project analyzes automotive customer journeys to identify process inefficiencies across delivery operations, complaints, and escalations. It generates actionable insights and visual dashboards to drive operational improvements.

📂 Project Overview
Objectives:

Map end-to-end workflows for automotive sales and after-sales service.

Analyze 12 months of operational data from a MySQL database.

Perform root cause analysis using Pareto charts and delivery delay metrics.

Create an Excel dashboard to track key performance indicators (KPIs).

Technologies Used:

Python

Pandas

Matplotlib

MySQL

OpenPyXL

⚙️ Features
Data Extraction:

Connects to a MySQL database.

Loads deliveries, complaints, and escalations tables.

Data Cleaning & Transformation:

Converts date fields to datetime objects.

Calculates delivery delays in days.

Merges datasets by customer_id.

Analysis:

Generates a Pareto chart to visualize complaint categories.

Computes KPI metrics for deliveries and complaints.

Reporting:

Builds a multi-sheet Excel dashboard:

Deliveries

Complaints

Escalations

Merged Data

KPI Summary

Saves Pareto chart as a PNG file.

