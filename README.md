# Unison

Note
-------------------------------------------------------------------------------
All relevant code is in the RMD file. All
explanation can be found on the 'about' page of the dashboard.
This project was a team effort. See the Task Breakdown section
for the responsibilities of each team member.


Task Breakdown
-------------------------------------------------------------------------------

Initals:

IE - Ibrahim Emam
AM - Ahmed Mokhtar
NK - Neha Kodali

Step 1: Data Prep (IE, AM, NK)

The first step consists of preparing the data that will be used for analysis. After importing the data, we streamlined the process of evaluating countries by using the most recent value for total cases and deaths. We then determined the population for each country, by averaging out the population during the 3 year period. Case and death rates per 100,000 were calculated. We identified 10 countries that met the required criteria, and calculated the case fatality rate (cfr) per 1,000 cases.

Step 2: Selecting Indicators (IE, AM)

The indicators of socioeconomic status selected were Gross National Income per capita, Universal Healthcare Coverage index, and population density. These were selected based on evidence from literature, in addition to the unique aspect of socioeconomic status they measure. Bar graphs were created for each one, plus a correlation plot to analyze their relationship to case fatality rates. 

Step 3: Create EDA-style figures for our chosen indicators (ggplot2):

GNI - IE
UHC - NK
PD - AM
corrplot - IE

Step 4: Pick best indicator and do statistical analysis (IE, AM)

Picked GNI per capita as indicator, conducted ANOVA and Tukey test to determine 
statistical significance, created boxplot to visualize findings

Step 5: Write 'About' section to explain the project (IE, NK)

Step 6: Copy code into RMD file and style appropriately (IE, AM, NK)

merge master - IE
