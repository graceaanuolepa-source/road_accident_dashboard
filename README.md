Project Overview
Road traffic casualties represent a significant public health challenge. This project analyzes over 400,000 casualty records to identify patterns, high-risk factors, and intervention priorities for transportation authorities and policy makers.
The Challenge
Transportation authorities need data-driven insights to:

Allocate limited safety resources effectively
Identify high-risk infrastructure requiring improvement
Target enforcement and education campaigns
Measure impact of existing interventions
Justify safety investments with evidence

The Solution
An interactive Excel dashboard that transforms raw casualty data into actionable intelligence across multiple dimensions: severity, vehicle type, geography, infrastructure, temporal patterns, and environmental conditions.

Critical Insights
1. Vehicle Type Analysis
Finding: Cars account for 79.8% of all casualties (333,485)
Implication: Vehicle safety features, driver education, and car-focused enforcement must be primary strategies
Recommendation: Mandate advanced safety features (AEB, lane departure warnings), enhanced driver training
Impact: 5% reduction in car casualties = 16,674 fewer victims annually

2. Infrastructure Priority
Finding: Single carriageways represent 74.1% of casualties (309,700)
Implication: This road type is the clearest priority for infrastructure investment
Recommendation: Central barriers, overtaking restrictions, junction improvements, speed management
Impact: Barriers reduce fatal head-on collisions by 50%+ (international evidence)

3. Urban Safety Challenge
Finding: 61.2% of casualties occur in urban areas despite lower speed limits
Implication: High traffic density and vulnerable road users create unique risks
Recommendation: 20mph zones, protected cycle lanes, traffic calming, pedestrian priority
Impact: Urban safety measures reduce pedestrian casualties by 30%+

4. Temporal Patterns
Finding: October-November show peaks (~20,000 casualties/month), 2022 improvement over 2021
Implication: Seasonal patterns allow proactive intervention; current initiatives working
Recommendation: Enhanced enforcement during peak months, seasonal campaigns, maintain successful programs
Impact: Targeted seasonal interventions reduce casualties by 10-15%

5. Weather Impact
Finding: 27.6% of casualties on wet roads (likely disproportionate to wet days)
Implication: Weather substantially increases crash risk
Recommendation: Enhanced drainage, weather-responsive speed limits, winter maintenance
Impact: Weather-responsive systems reduce wet-road casualties by 15-20%

6. Vulnerable Road Users
Finding: Bicycles: 33,672 casualties; significant vulnerable user impact
Implication: Cyclists lack vehicle protection; minor collisions = serious injuries
Recommendation: Segregated cycling infrastructure, junction redesign, driver awareness
Impact: Protected infrastructure reduces cyclist casualties by 40-50%

7. Progress Validation
Finding: 2022 shows improvement over 2021 (January: -31% casualties)
Implication: Existing interventions are working but need scaling
Recommendation: Maintain and expand successful programs, set ambitious targets (Vision Zero approach)
Impact: Sustained investment can achieve 50% reduction over 10 years

Technical Implementation
Data Preparation
Dataset Characteristics:

417,883 casualty records
Time period: 2021-2022
Multiple dimensions: severity, vehicle type, location, road type, light condition, road surface

Challenges & Solutions:
1. Missing Data (1,900+ records with blank road type)

Created "blank/other" category for transparency
Documented limitations in methodology
Maintained data integrity while acknowledging gaps

2. Categorical Standardization

Unified severity levels: Fatal, Serious, Slight
Standardized vehicle categories across 6 main types
Normalized road surface conditions: Dry, Wet, Snow/Ice

3. Temporal Feature Engineering

Extracted year, month, period from date fields
Enabled year-over-year comparison
Created seasonal analysis capability

4. Data Validation

Cross-checked totals across different aggregations
Verified percentage calculations
Ensured logical consistency across all fields

Dashboard Architecture
Design Principles:

Executive KPIs → Immediate severity context with percentage indicators
Vehicle Breakdown → Icon-based for quick visual recognition
Temporal Analysis → Line charts showing year-over-year trends
Geographic Split → Donut charts for part-to-whole relationships
Infrastructure Analysis → Bar charts for categorical comparison
Environmental Factors → Multiple dimensions (light, surface)
Interactive Filtering → Date sliders and location toggles

Dashboard Components
1. Executive KPI Cards
Four prominent metrics with percentage context:

Fatal casualties: 7,135 (1.7%)
Serious casualties: 59,312 (14.2%)
Slight casualties: 351,436 (84.1%)
Car-related casualties: 333,485 (79.8%)

2. Vehicle Type Breakdown
Casualties by mode of transport:

Cars: 333,485
Bicycles: 33,672
Trucks: 33,472
Buses: 12,798
Agricultural: 1,032
Other: 3,424

3. Monthly Trend Analysis
Year-over-year comparison (2021 vs 2022):

Identifies seasonal patterns
Shows improvement trajectory
Highlights peak months (Oct-Nov)

4. Geographic Distribution
Urban vs Rural split:

Urban: 255,900 casualties (61.2%)
Rural: 162,000 casualties (38.8%)

5. Infrastructure Analysis
Casualties by road type:

Single carriageway: 309,700 (74%)
Dual carriageway: 67,400
Roundabout: 26,800
One-way street: 7,400
Slip road: 4,700

6. Light Condition Analysis
Daylight vs Dark conditions:

Daylight: 305,000 (73%)
Dark: 112,900 (27%)

7. Road Surface Conditions
Impact of weather:

Dry: 279,445 (66.9%)
Wet: 115,261 (27.6%)
Snow/Ice: 23,177 (5.5%)

8. Interactive Filter Panel

Date range selection (2021-2023)
Urban/Rural toggle
Real-time dashboard updates


Skills Demonstrated
Data Analysis

Large-scale dataset management (400K+ records)
Multi-dimensional analysis across 6+ factors
Temporal trend identification
Geographic analysis
Risk assessment and prioritization

Technical Skills

Excel Advanced: PivotTables, PivotCharts, slicers, conditional formatting, data validation
Data Cleaning: Missing data handling, categorical standardization, feature engineering
Statistical Analysis: Descriptive statistics, percentage calculations, year-over-year comparisons
Dashboard Design: Layout, color theory, user experience, visual hierarchy

Analytical Thinking

Pattern recognition in complex datasets
Multi-factor analysis (severity × vehicle × location × infrastructure × environment)
Evidence-based recommendation development
Impact quantification
Stakeholder communication

Domain Knowledge

Public health perspective on road safety
Transportation planning and infrastructure
Policy analysis and implementation considerations
Risk assessment frameworks


Real-World Applications
For Transportation Authorities

Identify priority infrastructure investments (single carriageways)
Allocate enforcement resources based on patterns
Plan seasonal safety campaigns
Track progress toward safety targets

For Policy Makers

Evidence base for safety legislation
Justification for budget allocations
Evaluation of intervention effectiveness
Support for Vision Zero commitments

For Urban Planners

Data-driven decisions on traffic calming
Cycling infrastructure prioritization
Pedestrian safety improvements
Sustainable transport planning

For Public Health

Quantify public health burden (66,447 serious/fatal)
Target prevention campaigns
Assess health impact of interventions
Support injury prevention strategies
