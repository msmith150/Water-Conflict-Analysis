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
   
### Question 1 Analysis: Does water scarcity correlate with frequency and intensity of armed conflicts? (Matthew Smith)


### Question 2 Analysis: What are the geographical patterns of conflict relative to water scarcity? (Jason Britton)
In terms of the geographical patterns involved relative to water scarcity and conflict, we were able to show that water scarcity and conflict do overlap in the equaltorial region around the Middle East and Northern Africa. In an effort to bin one of the categories for an ANOVA test, we found water scarcity is divided into five categories.

--No Stress: Less than 25% of renewable resources are withdrawn.
--Low Stress: 25-50% of renewable resources are withdrawn.
--Medium Stress: 50-75% of renewable resources are withdrawn.
--High Stress: 75-100% of renewable resources are withdrawn.
--Critical Stress: More than 100% of renewable resources are withdrawn

The ANOVA test on water scarcity categories showed a strong correlation between maximum fatality rate over the 34 year time frame as a measure of conflict intensity in the region, and the five levels of water scarcity. The results indicated a p-value of 0.00026 showing a correlation between water scarcity levels and maximum fatality rate for the water scarce regions over the specified time frame. However, the residual of the ANOVA test was nearly twice as much as the sum of squares for the variation in water scarcity categories that were accounted for by the model. This suggests that while there is significant variation between stress categories, there's also considerable variation within each category that isn't explained by the stress level alone.

### Question 3 Analysis: Are certain types of conflicts more likely to occur in water-scarce regions? (Jason Britton)
Given the previous analysis, we conducted a Tukey post hoc test to determine which water scarcity levels were correlated to maximum fatality rates. The Tukey analysis reveals that the Medium Stress category is significantly different from Critical, Low, and No Stress categories in terms of the dependent variable, fatalmax2. This suggests that countries experiencing medium water stress levels have significantly different fatality rates compared to those with critical, low, or no water stress. The High Stress category, interestingly, does not show significant differences with other categories, which might warrant further investigation. The following boxplot shows the relationships between the water stress categories as they related to maximum fatality rates. ![image](https://github.com/user-attachments/assets/a4f0ca53-0c86-40af-9631-a681286a3b22)


### Question 4A Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Environmental Factors (Matthew Smith)


### Question 4B Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Socio-political factors (Chris Kellam)
Freedom Levels Analysis

Since 1980, the number of countries that are considered "Free" by "Our World in Data" has drastically increased, where in 1980 there were over 80 "Not Free" countries and just over 50 "Free" countries, but now there are over 80 Free countries and less than 70 Not Free and Partly Free countries.
The levels are defined as follows:
-Free countries are understood as countries in which citizens have many political rights (free and fair elections, political pluralism and participation, functioning government) and civil liberties (freedoms of expression and association, rule of law, personal autonomy).
-Partly free country are countries in which citizens have some political rights and civil liberties.
-Not free country are countries in which citizens have few political rights and civil liberties.

For this project, I was especially interested to find out if there is a correlation between the changes in the number of Not Free countries and the number of conflicts, as well as the Water Stress Levels. 
When the Not Free countries are compared to the number of Milatirzed Events per year, there seems to be some similarities. However, in the statisical analysis, Pearson's r for this correlation was 0.04, and the p-value was 0.8017, indicating that there is a weak positive correlation between the Not Free Country and Total Conflict variables, and any correlation that is present has a high probability of occurring by random chance.
The comparison between Not Free Countries and Average Water Stress level also seems to have a correlation, however Pearson's r was -0.09, indicating even less correlation between the two, and a p-value of 0.6017 also indicates that the weak correlation probably occurred by random chance.

Per Capita Income Level Analysis
"Our World in Data" split the countries of the world into 7 groups by Per Capita Income. Most countries in the world fall into the $2000-$49999 Per Capita Income range. 
Countries in the $2000-$50000 Per Capita Income range experienced higher levels of conflict than the other income bins. 

We wanted to see if there was any correlation between being in a specific income level and experiencing higher levels of conflicts.  
The statistical analysis showed with a Pearson's r of 0.39 that the correlation between these two variables is moderate to strong, meaning countries in the $2000-4999 bin are more likely to experience conflict. The p-value of 0.0210 shows that the observed correlation is statistically significant. 

### Question 4C Analysis: Are there other factors that affect the frequency of armed conflicts in water scarce areas? Geographical (Molly Fox)
The goal of this topic is to analyze other possible geographical factors that could contribute to a rise in militarized events. The three geographcial factors that were selected to investigate were precipitation, freshwater per capita, and change in surface temperature.

#### Surface Temperature vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of conflicts and the average change in surface temperature (F), there does not appear to be a strong correlation. The calculated r-value is 0.00, indicating no linear correlation. This means that change in surface temperature is not a good predictor for militarized events, and of the three geographical factors analyzed it is the weakest correlation.

#### Precipitation vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of militarized events and the average precipitation (mm/yr), at first glance, there appears to be a slight correlation. However, the calculated r-value is 0.06 with a negative slope, indicating a very weak negative linear correlation. This means that precipitation is not a good predictor for militarized events.

#### Freshwater vs. Conflicts 1980-2014 (Timescale Bar and Line Charts)
When looking at trends over time between the number of militarized events and the average freshwater per capita (m3), at first glance, there appears to be a slight correlation. The calculated r-value is 0.22 with a positive slope, indicating a weak positive linear correlation. This means that freshwater per capita alone is not a good predictor for militarized events, but of the three geographical factors analyzed it is the strongest correlation.


### Conclusions
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
