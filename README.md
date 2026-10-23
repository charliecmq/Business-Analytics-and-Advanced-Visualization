# The Illusion of Averages: U.S. County Health & Infrastructure Dashboard

🔗 **[View the interactive dashboard on Tableau Public](https://public.tableau.com/views/SpatialDisparitiesinU_S_InfrastructureandHealth/Story1)**

<!-- To add a preview image: export a screenshot of your dashboard, upload it to an `images/` folder in this repo, then uncomment the line below. -->
<!-- ![Dashboard Preview](images/dashboard-preview.png) -->

## Overview

Does a wealthier state necessarily provide better living conditions for its residents?

**The Illusion of Averages** is a data visualization project that investigates the relationship between economic prosperity, digital infrastructure, housing conditions, food access, and drinking water safety across the United States.

Using 2025 County Health Rankings data, this project explores how state-level averages can conceal significant inequalities between counties. While some wealthy states achieve high broadband access, they may still face severe housing problems, poor food environments, and drinking water violations in vulnerable communities.

The dashboard takes a closer look at these disparities by moving from a national and state-level perspective to individual counties, revealing where critical infrastructure and public health challenges remain hidden.

## Research Objectives

- Examine whether higher state income is associated with better infrastructure and living conditions.
- Compare broadband access with severe housing problems to identify different development patterns.
- Investigate disparities in food environments and drinking water safety at the county level.
- Identify the most vulnerable counties and propose targeted policy interventions.

## Dashboard Features

### 1. Macro Dashboard: State-Level Analysis

The macro dashboard provides an overview of development disparities across U.S. states.

Key visualizations include:

- **Income Map:** Visualizes state-level 80th percentile income.
- **Technology vs. Shelter Scatterplot:** Compares broadband access with severe housing problems using fixed national averages.
- **Four Development Quadrants:** Classifies states into distinct development patterns based on their performance across both dimensions.

The four quadrants are:

| Quadrant | Interpretation |
|---|---|
| Double Disadvantage | Low broadband access and high severe housing problems |
| Underdeveloped | Low broadband access and relatively stable housing |
| Tech ≠ Shelter | High broadband access but high severe housing problems |
| Balanced Development | High broadband access and relatively stable housing |

National reference thresholds:
- Broadband access: 85.78%
- Severe housing problems: 13.85%

### 2. Micro Dashboard: County-Level Analysis

The micro dashboard examines inequalities within individual states and identifies counties facing multiple disadvantages.

Key visualizations include:

- **Food Environment Dumbbell Chart:** Highlights differences between the highest and lowest county food environment index values within a state.
- **County-Level Bubble Chart:** Examines relationships between broadband access, food environment conditions, and drinking water violations.
- **Action Plan Highlight Table:** Identifies the worst-performing counties across selected development and public health indicators.

Additional metrics include:

- **Food Environment Index:** A scale from 0 to 10, where higher values indicate a better food environment.
- **Water Violations:** Indicates whether drinking water violations have been recorded.

## Key Findings

### California: The Technology–Shelter Paradox

California demonstrates that strong digital connectivity does not necessarily translate into better living conditions.

Despite broadband access approaching 90%, more than 21% of the state experiences severe housing problems. At the county level, Imperial County illustrates how housing challenges, a low food environment index, and drinking water violations can coexist within a wealthy state.

### Texas: The Rural Penalty

Texas reveals substantial differences in food environments across counties, with an observed gap of 8.8 points between the highest and lowest food environment index values.

Zapata County illustrates the concentration of disadvantages in rural communities, including poor performance across selected broadband, housing, and food environment indicators, alongside drinking water violations.

### Wisconsin: A Balanced Development Benchmark

Wisconsin serves as a comparison point, combining 86.79% broadband access with 11.37% severe housing problems. Its performance illustrates a more balanced relationship between digital connectivity and housing conditions.

## Policy Implications

The findings suggest that public investment should reflect the specific challenges faced by each county rather than relying solely on state-level economic indicators.

- **Technology–Shelter Paradox Areas:** Prioritize affordable housing, improved food access, and drinking water infrastructure instead of focusing exclusively on expanding broadband.
- **Double Disadvantage Areas:** Invest in foundational infrastructure, including rural broadband connectivity and emergency food assistance.
- **County-Level Targeting:** Use granular data to direct resources toward communities with the greatest concentration of unmet needs.

## Data Sources

The project uses 2025 County Health Rankings data and associated socioeconomic, infrastructure, housing, food environment, and drinking water indicators.

Please refer to the original data sources and project documentation for detailed definitions, geographic coverage, and calculation methods.

## How to Use the Dashboard

1. Start with the **Macro Dashboard** to explore state-level income and development patterns.
2. Use the scatterplot to compare broadband access and severe housing problems.
3. Hover over individual states to inspect their metrics and select states of interest.
4. Navigate to the **Micro Dashboard** to explore county-level disparities.
5. Use the dumbbell chart, bubble chart, and highlight table to identify vulnerable counties.
6. Return to the macro view to compare findings across states.

## Tools Used

- **Tableau** — dashboard design and interactive visualizations
- **Tableau Public** — hosting and sharing

## Repository Contents

- `Assignment 1_Chin Mun Qin.twb` — Tableau workbook containing the full dashboard and story.
- `README.md` — project documentation.
- `LICENSE` — license terms for this repository.

## Conclusion

The Illusion of Averages demonstrates why economic prosperity and state-level averages are insufficient measures of community well-being.

By examining disparities at the county level, the project reveals where digital progress coexists with housing insecurity, poor food environments, and drinking water challenges. The ultimate goal is to support more targeted, evidence-based policies that address the actual needs of vulnerable communities.

## Author

**Chin Mun Qin**

---

*This project was developed for data exploration and public policy analysis. The findings reflect the selected indicators and methodology and should be interpreted within the limitations of the underlying data.*
