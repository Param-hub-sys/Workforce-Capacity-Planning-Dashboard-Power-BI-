# Workforce-Capacity-Planning-Dashboard-Power-BI-
This project demonstrates an end-to-end capacity planning solution built in Power BI to support workforce management (WFM) decisions. It models how changes in demand impact workload, required staffing (FTE), and overall capacity utilization.
🔍 Overview

The dashboard uses historical data and dynamic inputs to:

Forecast demand
Calculate workload using AHT (Average Handling Time)
Estimate required FTE considering shrinkage
Compare against available FTE
Identify capacity gaps (overstaffed / understaffed scenarios)
Simulate demand changes using What-if analysis
⚙️ Key Features
📈 Forecast Volume Calculation
⏱️ Workload Hours Estimation
👥 Required vs Available FTE Analysis
🔴🟢 Capacity Gap Indicator with Conditional Formatting
🎯 Occupancy Tracking with Target Benchmark
🎛️ Scenario Analysis (What-if Parameter for Demand Increase)
📊 Interactive visuals and drill-down capabilities
🧮 Core Calculations
Adjusted Volume = Forecast Volume × (1 + Rework %)
Workload Hours = (Adjusted Volume × AHT) / 60
Required FTE = Workload / (Productive Hours per FTE)
Capacity Gap = Available FTE − Required FTE
Occupancy = Workload / (Available FTE × Working Hours)
🛠️ Tools & Technologies
Power BI
DAX (Data Analysis Expressions)
Excel (Dataset preparation)
📌 Business Use Case

This dashboard helps organizations:

Plan hiring and staffing levels
Identify under/over staffing risks
Optimize resource utilization
Perform scenario-based decision making
<img width="1123" height="738" alt="image" src="https://github.com/user-attachments/assets/d289e43a-ac87-4ea2-b0f2-94b4632f5b10" />

🚀 Future Enhancements
Demand forecasting using time series models
SLA calculation using Erlang C
Attrition and hiring plan modeling
Automated data refresh pipeline
