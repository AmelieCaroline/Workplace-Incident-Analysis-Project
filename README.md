# Workplace Incident Analysis Dashboard – Power BI Portfolio Project

---

## Overview

This Power BI project analyzes 514 workplace safety incidents recorded across multiple plants, departments, and shifts between January 2020 and December 2022. The goal is to identify patterns in incident frequency, severity, and cost — and surface actionable insights to reduce operational risk and improve workplace safety.

The dashboard was designed to help organizations:

* Monitor workplace safety performance across plants and departments
* Identify high-risk incident categories (burns, falls, slip/trips)
* Analyze the financial and human cost of incidents over time
* Support data-driven safety improvement decisions

The dashboard includes KPI monitoring, trend analysis, drill-down exploration, operational risk comparisons, and root-cause analysis using a line and clustered bar chart with dual axis.

---

## Tools & Technologies

* **Power BI** – Dashboard design & data visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – KPI calculations and measures
* **Excel / CSV datasets** – Source data (Workplace Safety Dataset.xlxs)

---

## Key Metrics at a Glance
* Total Incidents: 514
* Total Incident Cost: $717,800
* Total Lost Days: 378.5
* Average Days Lost per Incident: 0.74
* Lost Time Rate: 73.64%

Over 73% of incidents resulted in lost work time — highlighting a significant human and productivity impact beyond direct medical costs.

--- 

## Report Pages

### Executive Dashboard
High-level overview of workplace incidents through KPIs and summary visualizations.

* Total incidents, cost, lost days, and lost time rate
* Incident distribution by plant (Montana 12.45% → Purchasing 8.37%)
* Incident distribution by department (Shipping leads at 13.23%)
* Interactive year slicer (2020, 2021, 2022)

### Incident Overview

Focuses on understanding the distribution of incidents across categories and operational areas.

* Most common incident types: Burn (65), Fall (63), Slip/Trip (62)
* Incident frequency by department and shift
* Gender breakdown: Male 89.11% | Female 10.89%
* Top injury body locations: Back (51), Feet (49), Head (49)

### Trends & Risk Severity

Analyzes how workplace incidents evolve over time and highlights risk patterns.

* Monthly incident trend (Jan 2020 – Dec 2022): peaks in March (56), July (55), January (53)
* Shift distribution: Day 34.63% | Night 34.24% | Afternoon 31.13%
* Workday risk: Tuesday (87) and Friday (82) are the highest-risk days
* Report type breakdown: Near Miss (139) → First Aid (114)

### 4. Impact Analysis

Examines the operational and financial impact of workplace incidents.

* Days lost by department: Fabrication leads (60 days) despite lower incident count
* Total cost by plant: Florida highest, California lowest
* Age group analysis: 25–34 most affected (29.57%), 18–24 least (20.62%)
* Days Lost vs. Incident Count scatter: negative correlation — fewer but more severe incidents in some types

---

### 5. Root-Cause Insights

Cross-departmental analysis of incident type, cost, and severity.

* Top cost combinations: Shipping Slip/Trip ($19,137), Shipping Cut ($18,058), Maintenance Equipment ($17,579)
* Burn injuries span 4+ departments: Finishing, Maintenance, Painting, Melting
* Vehicle incidents: low frequency (50 cases) but disproportionately high cost and lost days
* Percentage of incident types by department and gender

---

## Key Insights
🔴 Insight 1 — Shipping Is the Highest-Risk, Highest-Cost Department
Shipping accounts for the most incidents (13.23%) and appears three times in the top 10 costliest incident combinations. Slip/trips and cuts in Shipping alone cost nearly $20K each. Anti-slip flooring, cut-prevention PPE, and workflow safety audits are the clearest intervention targets.
🔴 Insight 2 — Fabrication: Fewer Incidents, But Most Days Lost
Despite ranking 8th in incident frequency (9.73%), Fabrication leads all departments in lost days (60). This signals more severe injuries per event — likely due to machinery and falling object hazards. Machine guarding and PPE compliance require immediate attention.
🟠 Insight 3 — Burns Are the Most Pervasive Incident Type
Burns are the single most frequent incident type (65 cases) and appear as high-cost events across Finishing, Maintenance, Painting, and Melting. A cross-departmental burn prevention program — heat-resistant PPE, equipment maintenance schedules, and handler training — is warranted.
🟠 Insight 4 — Vehicle Incidents Punch Above Their Weight
Vehicle incidents rank 8th in frequency but carry some of the highest per-case costs and lost workdays. Forklift safety training and pedestrian/vehicle traffic management in work zones should be reviewed.
🟡 Insight 5 — No Sustained Improvement Trend (2020–2022)
The monthly time series shows no consistent downward trajectory across the three-year period, with incident counts fluctuating between ~10–26/month. Current safety measures are not producing measurable gains — a programmatic review is recommended.







Insight 1

“Most high-cost incidents originate from lost-time cases within operational departments such as Fabrication and Painting.”

Insight 2

“Vehicle incidents show relatively low frequency but high operational impact due to increased lost workdays and costs.”

Insight 3

“Near misses occur more frequently during afternoon shifts, indicating potential operational fatigue or workflow congestion.”
---

# Interpretations & Insights

## Executive Dashboard Interpretations

### Incident Concentration

The dashboard reveals that workplace incidents are not evenly distributed across all categories. A small number of categories account for the majority of incidents, suggesting that safety improvement efforts should prioritize these high-frequency areas.

### Severity Monitoring

The severity analysis shows that while many incidents are classified as low or medium severity, high-severity incidents still represent a critical operational risk due to their potential financial and human impact.

### Trend Observation

The incident trend visualizations indicate fluctuations over time, which may reflect seasonal operational changes, staffing variations, or changes in safety compliance.

### Operational Performance

Departments with consistently higher incident counts may require additional safety training, process reviews, or stronger compliance monitoring.

---

## Incident Overview Interpretations

### Most Frequent Incident Types

The analysis identifies the most commonly reported workplace incidents, allowing organizations to focus preventive strategies on the most recurring safety risks.

### Department Comparison

Some departments experience significantly more incidents than others, which may indicate differences in work conditions, equipment usage, or safety policy enforcement.

### Reporting Patterns

The visualizations suggest that incident reporting behavior may vary across operational areas. Higher reporting rates may indicate stronger safety awareness rather than worse safety performance.

---

## Trends & Risk Severity Interpretations

### Rising or Declining Trends

The time-series analysis helps determine whether workplace safety performance is improving or deteriorating over time.

### High-Risk Periods

Certain periods show spikes in incident frequency or severity, which may correspond to operational pressure, staffing shortages, or environmental factors.

### Severity Distribution

The dashboard highlights the relationship between incident frequency and severity, showing whether the organization primarily faces frequent minor incidents or fewer but more severe incidents.

---

## Impact Analysis Interpretations

### Business Impact

Incidents with higher severity levels likely contribute to increased operational disruptions, financial costs, and productivity loss.

### Preventive Prioritization

Departments or categories with both high frequency and high severity should be prioritized for preventive safety measures.

### Decision Support

The dashboard provides management with actionable insights that can guide resource allocation, employee training, and policy improvements.

---

# Skills Demonstrated

This project demonstrates the following business intelligence and data analytics skills:

* Data cleaning and preparation
* KPI development using DAX
* Dashboard storytelling
* Data visualization best practices
* Trend analysis
* Risk analysis
* Business insight generation
* Interactive dashboard design

---

# Business Value

This dashboard enables organizations to:

* Improve workplace safety monitoring
* Reduce operational risks
* Support proactive decision-making
* Identify recurring safety issues early
* Enhance compliance and reporting visibility


# Recommended Screenshots for GitHub

Include:

1. Main dashboard overview
2. KPI section
3. Trend analysis page
4. Severity analysis visuals
5. Interactive slicers and filters

---

# Suggested LinkedIn Project Description

🚨 Workplace Incident Analysis Dashboard | Power BI

Developed an interactive Power BI dashboard to analyze workplace incident data and identify operational safety risks.

Key highlights:

* Built KPI-driven executive dashboard
* Analyzed incident severity and risk trends
* Identified high-risk operational areas
* Created interactive filters and drill-down visualizations
* Generated actionable insights to support workplace safety decisions

Skills used: Power BI, DAX, Power Query, Data Visualization, Risk Analysis, Dashboard Design

#PowerBI #DataAnalytics #BusinessIntelligence #Dashboard #DataVisualization

---

# Tips Before Uploading to GitHub

* Export high-quality screenshots from Power BI
* Add a professional banner image for the repository
* Keep the README concise and visually organized
* Include a short project objective at the top
* Add a “Key Insights” section with 3–5 important findings
* If possible, include sample datasets or anonymized data

---

# Optional Enhancements

Future improvements could include:

* Predictive risk modeling
* Incident forecasting
* Real-time dashboard integration
* Automated alerts for high-severity incidents
* Geographic incident mapping
* Root cause analysis visuals

