# Project1_Team2_repo

## Analyzing the Relationship Between Conflict and Water Scarcity

## Team Members
- Chris Kellam
- Matthew Smith
- Jason Britton
- Molly Fox

## Project Description
This project aims to explore the complex relationship between armed conflict and water scarcity by integrating and analyzing datasets from various sources. We will leverage geospatial and environmental data to assess how water scarcity influences the occurrence and intensity of conflicts. This analysis will help to understand whether areas with significant water stress experience higher levels of conflict and how water scarcity impacts socio-political stability.

## Project Tasks
1. Data Collection: Define conflict and water scarcity, then retrieve conflict and water scarcity data from relevant APIs.
2. Data Processing: Clean and format the collected data.
3. Data Integration: Merge datasets to facilitate analysis.
4. Analysis & Visualization: Perform statistical and geospatial analysis to identify correlations and patterns and create visualizations to represent findings and insights.

## Hypothesis
Water is one of the most critical resources on the planet for human survival and only 0.5% of the world's water is available for human use. Our hypothesis is that when the demand for water exceeds the supply (water scarcity) the total number of global conflicts increases.

## Research Questions to Answer
1. Does water scarcity correlate with frequency and intensity of armed conflicts? (Matthew Smith)
2. What are the geographical patterns of conflict relative to water scarcity? (Jason Britton)
3. Are certain types of conflicts more likely to occur in water-scarce regions? (Jason Britton)
4. Are there other factors that affect the frequency of armed conflicts in water scarce areas?
  - A. Environmental Factors (Matthew Smith)
    * Global GDP
    * Global CO2 Emissions
  - B. Socio-political factors (Chris Kellam)
    * Per-capita income
    * Degree of political freedom
  - C. Geographical (Molly Fox)
    * Change in Surface Temperature
    * Precipitation
    * Freshwater Per Capita
   
## Question 1 Analysis: Does water scarcity correlate with frequency and intensity of armed conflicts? (Matthew Smith)


## Question 2 Analysis: What are the geographical patterns of conflict relative to water scarcity? (Jason Britton)


## Question 3 Analysis: Are certain types of conflicts more likely to occur in water-scarce regions? (Jason Britton)


## Question 4A Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Environmental Factors (Matthew Smith)


## Question 4B Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Socio-political factors (Chris Kellam)


## Question 4C Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Geographical (Molly Fox)
The goal of this topic is to analyze other possible geographical factors that could contribute to a rise in militarized events. The three geographcial factors that were selected to investigate were precipitation, freshwater per capita, and change in surface temperature.

### Surface Temperature vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of conflicts and the average change in surface temperature (F), there does not appear to be a strong correlation. The calculated r-value is 0.00, indicating no linear correlation. This means that change in surface temperature is not a good predictor for global conflict, and of the three geographical factors analyzed it is the weakest correlation.

### Precipitation vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of militarized events and the average precipitation (mm/yr), at first glance, there appears to be a slight correlation. However, the calculated r-value is 0.06 with a negative slope, indicating a very weak negative linear correlation. This means that precipitation is not a good predictor for militarized events.

### Freshwater vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of militarized events and the average freshwater per capita (m3), at first glance, there appears to be a slight correlation. The calculated r-value is 0.22 with a positive slope, indicating a weak positive linear correlation. This means that freshwater per capita alone is not a good predictor for militarized events, but of the three geographical factors analyzed it is the strongest correlation.


## Conclusions
Analysis suggests there is a moderate positive correlation between conflict and water stress. Although other variables also showed a positive correlation to conflict, water stress was by far the strongest. Analysis did not provide information on causation (increased water stress causes increased conflict or increased conflict causes more water stress), but results suggests there is an opportunity for further study to explore this correlation.

## Data Sources
* Bureau of Reclamation: Global Water - https://www.usbr.gov/mp/arwec/water-facts-ww-water-sup.html
* Food and Agriculture Organization (FAO): Water Stress - https://data.apps.fao.org/aquastat/?lang=en
* University of Alabama: Militarized Events - https://internationalconflict.ua.edu/data-download/
* Correlates of War (COW): Countries - https://correlatesofwar.org/data-sets/cow-country-codes-2/
* GitHub: Regions & Sub-Regions - https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv
* World Bank Group: Political Stability, Precipitation, Freshwater - https://databank.worldbank.org/reports.aspx
* International Monetary Fund: Surface Temperature - https://www.imf.org/en/Home
* Our World In Data: Political Regime - https://ourworldindata.org/grapher/political-regime-fh
* Our World in Data: GDP Per Capita - https://ourworldindata.org/grapher/gdp-per-capita-worldbank?time=latest
