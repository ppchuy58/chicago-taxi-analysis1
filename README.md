🚕 Chicago Taxi Trips Analysis
📊 Project Overview

This project performs an exploratory data analysis (EDA) of taxi trips in Chicago to identify:

Which taxi companies completed the most trips.

Which neighborhoods receive the highest number of drop-offs.

Market concentration among operators.

Urban mobility patterns.

The analysis focuses on data from November 15–16, 2017.

🎯 Objectives

Rank taxi companies by total number of trips.

Identify the top neighborhoods by trip completion volume.

Detect demand concentration areas.

Provide business insights for fleet optimization.

🗂 Dataset

Source: Chicago Taxi Trips public dataset.

Main fields:

company_name

trips_amount

dropoff_area

trip_end_location

date

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Jupyter Notebook

🔄 Analysis Process
1️⃣ Data Loading & Exploration

Imported CSV files.

Reviewed structure and missing values.

Generated descriptive statistics.

2️⃣ Data Cleaning

Removed records with missing company names.

Converted date fields.

Grouped data by company and neighborhood.

3️⃣ Analysis

Ranked companies by total trips.

Calculated the top 10 neighborhoods by drop-off volume.

Identified demand concentration patterns.

4️⃣ Visualization

Horizontal bar charts for trips by company.

Top 10 neighborhoods charts by average trips.

📈 Key Findings

Flash Cab led total trips during the analyzed period.

A small group of companies dominates the market.

Loop was the most frequent drop-off area.

River North and Streeterville also showed high activity.

Demand is highly concentrated in central and tourist districts.

💡 Business Conclusions

Large fleets can focus vehicle availability in high-demand zones.

Companies may optimize shift planning around central districts.

Competitive pressure is strongest among top operators.

Mobility demand shows strong urban clustering.

📂 Repository Structure
├── notebook.ipynb
├── data/
│   └── chicago_taxi.csv
├── images/
│   └── charts.png
└── README.md

What This Project Demonstrates

Exploratory Data Analysis (EDA)

Data cleaning & transformation

Aggregations and grouping

Data visualization

Business storytelling

📬 Contact

José Cabral
Aspiring Data Analyst
LinkedIn:https://www.linkedin.com/in/jos%C3%A9-de-jes%C3%BAs-cabral-anguiano-586850392/
