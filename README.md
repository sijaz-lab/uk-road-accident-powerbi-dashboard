# UK Road Accident Analysis Dashboard (Power BI)

## Objective
To analyse UK road accident data and identify patterns related to accidents
severity, speed limits, road types, light conditions, and geographic distribution
to support road safety insights and decision-making.

## Tools Used
- Power BI
- Power Query
- DAX
- Excel

## Data Preparation
The road accident dataset was imported into Power BI and cleaned using
Power Query. This included handling missing values, standardising formats,
and ensuring column consistency. Additional calculated columns and measures
were created to support accident severity analysis.

## Data Model & DAX
Calculated measures were created using DAX to classify accidents into
Fatal, Serious, and Slight categories. Relationships between tables were
maintained in the model view to ensure accurate and meaningful visualisations.

Key measures include:
- Total Accidents
- Total Casualties
- Fatal, Serious, and Slight Accident Counts

## Dashboard Design
The dashboard includes multiple interactive visuals:
- Slicers for Vehicle Type, Weather Conditions, and Road Surface Conditions
- Donut charts for Urban vs Rural accidents and casualties by light conditions
- Area chart showing accidents by speed limit and severity
- Stacked bar chart displaying casualties by road type
- Line chart showing monthly accident trends
- Filled map visualising accident distribution across the UK

## Key Insights
- Over 308K total accidents and 418K total casualties recorded
- The majority of accidents occur at lower speed limits (around 30 km/h)
- Serious and slight accidents are significantly more common than fatal accidents
- Single-carriageway roads account for the highest number of casualties
- Higher accident frequency observed in urban areas compared to rural areas
- Most casualties occur during daylight conditions
- Geographic clustering of accidents is visible across multiple UK districts

## Challenges
- Data cleaning was critical to remove inconsistencies and missing values
- Designing a clear and user-friendly dashboard required careful visual selection
- Balancing insight depth with dashboard readability was a key challenge

## Impact
This dashboard enables stakeholders to quickly identify high-risk conditions
and locations, supporting targeted road safety interventions and improved
decision-making.
