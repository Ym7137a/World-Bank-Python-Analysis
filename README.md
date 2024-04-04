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
