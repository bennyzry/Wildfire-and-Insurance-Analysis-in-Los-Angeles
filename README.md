## 📌 Note from Contributor

This repository is a personal fork of a team project originally hosted at [jl3443/Wildfire-and-Insurance-Analysis-in-Los-Angeles](https://github.com/jl3443/Wildfire-and-Insurance-Analysis-in-Los-Angeles). It is included in my GitHub portfolio to demonstrate my contributions in data engineering, geospatial processing, and dashboard visualization.

During the project, I contributed to:
- Building Apache Spark data pipelines for large-scale wildfire and insurance data
- Performing geospatial multipolygon processing and zip code mapping
- Designing and publishing interactive Tableau dashboards
- Managing cloud deployment and data access via DuckDB on AWS EC2

---

# Wildfire-and-Insurance-Analysis-in-Los-Angeles
[🔗 Tableau Dashboard Link](https://public.tableau.com/app/profile/violet.ahmat/viz/405FinalProject-CAFireInsurance/MappingEarnedPremiumsInsuranceRiskbyZipCode?publish=yes)
This is the interactive Tableau dashboard for our project, visualizing wildfire-related insurance risks and premiums across Los Angeles zip codes.

🧠 Project Overview
This project visualizes and analyzes the relationship between fire risk, insurance premiums, and earned exposure across Los Angeles and surrounding California regions. Using zip-code-level data, we explore how wildfire events impact insurance costs and underwriting decisions over time.

🎯 Objectives
Map earned premiums and risk scores by zip code.
Visualize the correlation between fire risk and insurance costs.
Compare insurance exposure across different agencies and years.
Profile key wildfire events and analyze their impact on insurance metrics.

📊 Key Dashboards
1. Geospatial Distribution
Earned Premium vs. Risk Score by ZIP Code
Fire Risk Score vs. All-Risk Score heatmap
Interactive filters by year and fire name

3. Time Series Analysis
Yearly trend of Average Risk Scores (2017–2022)
Earned Premium vs. Risk Score Correlation scatterplot

3. Agency-Level Breakdown
Earned Premium and Exposure by Agency (e.g., CDF, LRA, CCO)
Comparative analysis from 2018 to 2021

4. Fire-Level Impact Analysis
Fire-specific insurance metrics for major events (e.g., Woolsey, Camp, Getty, Saddle Ridge)
Metrics include earned premium, exposure, burned acreage, and risk score

6. Region-Level Case Study
Specific focus on AGUA CALIENTE, NETTLE, MOUNTAIN VIEW, etc.
Drill-down on exposure and premium trends by agency and year


🛠 Tools Used
Tableau Public
Mapbox / OpenStreetMap (for geospatial layers)
CSV/GeoJSON data (assumed from project context)
Future enhancement: integrate with AWS-hosted wildfire datasets or FEMA API

📈 Potential Extensions
Predictive modeling of fire-related premium changes using machine learning
Real-time integration with fire incident reports
Adding socio-demographic overlays (income, housing density)
