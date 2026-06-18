# solar-adoption-victoria-ARENA
Investigation of factors influencing solar adoption in Victoria using solar, housing price, and Census dwelling data.

Project Overview:

This project investigates the key factors influencing residential solar energy adoption across Melbourne and broader Victorian postcode areas using a combined postcode-year dataset covering 2014 to 2024. The analysis integrates multiple data sources, including solar market data, ABS dwelling structure Census data, and Victorian Government house sales data to identify the demographic, housing, and spatial characteristics associated with solar uptake.

At the time of this analysis, the most recent available ABS Census was the 2021 Census. The next Census will be conducted in 2026, and its dwelling structure data had not yet been released. Therefore, dwelling structure data from the 2011, 2016, and 2021 Censuses was used as the latest official benchmark and interpolated across the study period to estimate annual dwelling composition at the postcode level.

The objective of this project is to understand which factors most strongly influence solar adoption and provide evidence-based recommendations for policymakers and renewable energy stakeholders.

The main business question is:

What factors influence solar energy adoption in Melbourne, and how can these insights support more targeted solar policy and investment decisions?

The project evaluates the following key themes:

* Whether detached-house suburbs have higher solar adoption.
* Whether apartment-heavy suburbs have lower solar adoption.
* Whether house prices are positively or negatively associated with solar adoption.
* Whether distance from Melbourne CBD is associated with solar adoption.
* Whether high property-count suburbs have higher adoption rates or simply higher total installations.
* Whether different postcode-level solar market segments can be identified using clustering analysis.

Data Sources:

ARENA solar installation and adoption data (2014-2024)
Victorian Government house sales data (2014–2024)
ABS Census dwelling structure data (2011, 2016, and 2021)
Melbourne CBD distance calculations
Postcode boundary data for spatial analysis

Methods:

- Data Cleaning and Transformation
- Data Integration and Feature Engineering
- Census Data Interpolation
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Hypothesis Testing
- Geospatial Analysis using GeoPandas
- Data Visualization (Heatmaps, Scatter Plots, Pairplots, Maps)

Key Findings:

- Dwelling Structure Is the Strongest Driver
- Detached housing is strongly associated with higher solar adoption.
- Apartments and townhouses are associated with lower adoption rates.
- Location Matters
- Outer suburbs generally have higher solar adoption than inner-city areas.
- Distance from Melbourne CBD is positively related to solar uptake.
- House Prices Have Limited Influence
- Higher house prices do not necessarily lead to higher solar adoption.
- Housing type and location are stronger predictors than property value.
- Property Count Affects Volume, Not Adoption Rate
- Larger suburbs have more installations overall.
- Adoption rate is a better measure of solar uptake than installation volume.

Business Value:

This analysis provides actionable insights for ARENA, policymakers, energy providers, and sustainability stakeholders seeking to accelerate residential solar adoption across Victoria.

The findings suggest that solar adoption programs should be prioritised based on dwelling structure, location type, postcode segment, and adoption gap rather than relying solely on property count or property price.
