# 🌎 Covid-19 World Vaccination Progress Dashboard

Built an interactive map chart to see the vaccination progress for each countries, the types of vaccines used across the country, the percentage of people who Once Vaccinated vs Fully Vaccinated, and to find out region with the lowest vaccination rates.
**Tools** : Tableau

## Overview
If 2020 was dominated by the news of how Covid -19 spread across the world, then 2021 has so far been focused on ending pandemic through vaccine distribution.

## Data Cleaning and Preparation
**Tools** : BigQuery and Google Sheets

**Data Cleaning steps:**
- Dropped unnecessary columns and rows using BigQuery.
- The total_vaccinations and people_vaccinated columns are cumulative values. To obtain the exact number of people vaccinated and total vaccinations per country, I extracted only the latest available record for each country using BigQuery.
- Added a Region column and created dummy variables in Google Sheets to identify the types of vaccines used in each country.
- Created a new variable: People Vaccinated Once, calculated using the formula: SUM(People Vaccinated) - SUM(People Fully Vaccinated).
- Exported the cleaned dataset and connected it to Tableau for visualization.

## ✨Insight
- More than 5.1 billion people worldwide have received a dose of a Covid-19 vaccine, equal to about 65.38 percent of the world population.
- There are 24 types of vaccines available which used across the world.
- Oxford/AstraZeneca is the most widely used vaccines in the world, in 183 countries. Followed by Pfizer/BioNTech in 158 countries.
- Asia used the most types of vaccines, up to 23 types of vaccines. While Australia used the least types of vaccines, only 3 types of vaccines. Astra Zeneca  still be the dominant vaccine used on every region, especially in Europe region.
- Most daily vaccinations are in Asia, then followed by Africa.
- China, India, United States, Brazil and Indonesia are the top 5 country with the most of total vaccinations in the world.
- People in the Europe region get the Full Vaccinated much faster, leaving only 3.68 percent who only get Vaccinated Once. While Africa is the region with the lowest of Full Vaccination rate.

## Recommendation
- Start increasing vaccinations for people who are only vaccinated once to get the fully vaccinated according to the vaccinations scheme and health protocol suggested by WHO.
- Start increasing the number of vaccinations for some countries that may lack access to vaccines. Such as underprivileged countries in the African continent which have low people vaccinations rate.

## Visualization
See full of my interactive story line in Tableau: [here](https://public.tableau.com/views/W10W11_16596100766930/CovidStory?:language=en-US&:display_count=n&:origin=viz_share_link)

![image](https://user-images.githubusercontent.com/100077706/185742808-9fcb5fd6-dd63-4352-9e42-db40bc8cd7a0.png) 
