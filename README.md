# Massachusetts Health Equity Analysis - Key Findings

Please note this writeup supports this notebook. To see visualizations you can go to # Massachusetts Health Equity Analysis - Key Findings

**Please note:** This writeup supports the main [analysis notebook](https://github.com/amanda-nathan/Health_Equity/blob/main/MA_Health_Equity_workflow.ipynb). 

**To view visualizations and maps**, please visit the notebook on nbviewer (GitHub doesn't render plots for this notebook):

👉 **[View Full Analysis with Visualizations](https://nbviewer.org/github/amanda-nathan/Health_Equity/blob/main/MA_Health_Equity_workflow.ipynb)**


**Data Sources**: CDC PLACES API + US Census ACS API  
**Temporal Scope**: Primarily 2022 data (91% of 2,000 records)  
**Geographic Scope**: 14 Massachusetts counties

## Statistical Findings

### Strong Social-Health Correlations
- **Obesity-Poverty**: r = 0.517 (strong positive correlation)
- **Obesity-Income**: r = -0.395 (income protection effect)  
- **Stroke-Income**: r = -0.369 (income protection effect)

### Geographic Health Disparities
- **Stroke**: 1.75x difference between counties
- **Obesity**: 1.69x difference between counties
- **Heart Disease**: 1.54x difference between counties

## Interactive Visualizations Created

### Three Evidence-Based Maps
1. **Social Vulnerability Map** - County-level poverty risk assessment
   - Red circles indicate high-risk areas (>5% poverty)
   - Circle size proportional to poverty rate
   - Identifies Hampden, Suffolk, Bristol as priority counties

2. **Health Outcomes Map** - Geographic distribution of obesity rates
   - Visual confirmation of health disparities across counties
   - Interactive popups show detailed health metrics
   - Demonstrates 1.69x variation in obesity rates

3. **Correlation Evidence Map** - Visualizes r=0.517 obesity-poverty relationship
   - Purple circles show dual high-risk areas (high obesity + high poverty)
   - Provides geographic evidence for statistical correlations
   - Interactive demonstration of social determinants theory

## High-Risk Counties Identified

| County | Poverty Rate | Median Income | Risk Profile | Map Evidence |
|--------|-------------|---------------|--------------|-------------|
| Hampden | 6.5% | $66,619 | Highest social vulnerability | Purple (dual high risk) |
| Suffolk | 5.3% | $87,669 | High stroke disparities | Red (high risk) |
| Bristol | 5.3% | $80,628 | Multiple health conditions | Red (high risk) |

## Policy Implications

### Immediate Priorities
- **Geographic targeting**: Interactive maps justify county-level interventions with clear visual evidence
- **Economic interventions**: Income consistently protects against poor health outcomes  
- **Stroke prevention**: Urgent need in Suffolk County communities
- **Dual-intervention approach**: Purple counties require both health and economic interventions

### Evidence Base
- **Robust sample size**: 2,000 health records across 5 conditions
- **Social determinants confirmed**: r = 0.517 obesity-poverty correlation with geographic validation
- **Income protection validated**: Consistent negative correlations with health risks
- **Geographic disparities**: Up to 1.75x difference visualized through interactive mapping
- **Actionable insights**: County-specific risk profiles enable targeted resource allocation


### Questions to Explore
- How might these insights influence current health equity initiatives?
- What additional data sources could strengthen this analysis?
- How could interactive mapping support community engagement efforts?
- What role might this methodology play in policy development processes?
