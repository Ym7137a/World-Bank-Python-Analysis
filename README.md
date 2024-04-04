# World-Bank-Python-Analysis

**Project Description:**

This project aims to analyze and visualize data provided by the World Bank, focusing on key indicators such as fertility rate, life expectancy, population, and regional classification for various countries over several decades. The data frames used in the analysis were obtained from the public data repositories of the World Bank.

**Data Description:**

country.csv: Contains information about countries, including their codes, regions, income groups, and full names.

fertility.csv: Provides data on fertility rates for each country from 1960 to 2017. Fertility rate is measured as total births per woman.

life_exp.csv: Includes life expectancy data for each country from 1960 to 2017, measured in years at birth.

population.csv: Presents population estimates for each country from 1960 to 2017, reflecting the total number of residents.

**Data Cleaning and Tidying:**

The provided data were initially messy, with multiple observational units per row. To adhere to the principles of tidy data, the data frames for fertility, life expectancy, and population were transformed into tidy formats, with one observational unit per row. This involved restructuring the data to have variables such as country name, country code, year, and the respective indicator values.

**Data Integration:**

The cleaned and tidied data frames were then merged to create a comprehensive data set. The final merged data frame includes information on fertility rate, life expectancy, population, and region for each country across various years.

**Data Visualization & Analysis:**

1. Scatterplot of Fertility Rate vs. Life Expectancy: A scatterplot was created to visualize the relationship between fertility rate and life expectancy, color-coded by region, for the years 1960, 1970, 1980, 1990, 2000, and 2010.
   
<img src="Visualizations/3.png" alt="Description of the image" width="500">


Line Plot of Total Population by Region Over Time: A line plot was generated to display the total population for each region over the years 1960 to 2010, excluding 2018. Each region is represented by a different color.

Bar Plot of Population by Region for 2017: A bar plot was created to illustrate the population distribution across different regions for the year 2017.


**Conclusion:**

This project demonstrates the process of data cleaning, tidying, integration, and visualization using Python libraries such as pandas, seaborn, and matplotlib. Through these visualizations, insights can be gained into global trends related to fertility, life expectancy, population dynamics, and regional disparities. The analysis provides valuable information for understanding socio-economic patterns and informing policy decisions aimed at improving public health and welfare worldwide.
