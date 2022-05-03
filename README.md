# Covid-19-Trends-Analysis
This repository contains analysis of Covid-19 cases around the world from [Worldometer](https://www.worldometers.info/) website. The data obtained in this case was processed and analysed for learning purposes. 
# The Analysis
The [Worldometer](https://www.worldometers.info/) website provides daily real-time updates on various global information, including Covid-19 updates. This data is organized in tables that are organized by origin.
## Focus
The analysis focuses on previous day data to determine the infections and outcomes of Covid-19
## What was done
The analysis scrapes the website form information, querying for specific tables of data. It then cleans the obtained data, removing null/empty values, spaces, and unnecessary characters. It also removed unnecessary fields that were determined to be unimportant to the analysis.

The analysis then computes the percentages of new cases, deaths, and recoveries recorded and determines whether there is a positive or negative shift. Finally, the analysis visualizes the processed data, categorizing it based on its origin and other specified attributes.