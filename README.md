# Suitable Sites Analysis for Private Schools in Toronto

## Date

December 2023

## Project Summary

### Introduction:
The project aimed to identify optimal locations for private schools in various neighborhoods of the Greater Toronto Area (GTA). Acknowledging the diversity of private schools, the study sought to leverage data analysis to identify potential sites based on factors such as income, proximity to existing schools, and population density.

### Data Sources:

Toronto Signature Sites:

Source: Toronto data portal

Attributes: Site name, geometry, unique identifier (_id)

Statistic Canada Census Data 2021 (Income Data):

Source: Census mapper API

Attributes: Neighborhood name, median income, geometry, unique identifier (name)

School Locations - All Types:

Source: Toronto data portal

Attributes: School type, geometry, unique identifier (_id)

Statistic Canada Census Data 2021 (Population Density Data):

Source: Census mapper API

Attributes: Neighborhood name, population count, geometry, unique identifier (name)

### Methodology/Analysis:

#### Neighbourhood Income vs Site Location:

Query: Identified top 20 sites with the highest neighborhood median income.
Considered income as a metric for potential demand for private education.

#### Proximity of Sites to Neighboring Schools:

Query: Determined top 20 sites with the lowest proximity to other schools within a 1 KM radius.
Evaluated competition and identified underserved areas for strategic positioning.

#### Population Density vs Site Location:

Query: Analyzed top 20 sites with the highest population density to gauge potential demand for education services.
Considered population density as an indicator of concentrated potential students.

#### Conclusion:
Three potential sites were initially identified based on income, proximity, and population density. However, visual inspection revealed that all three sites were no longer vacant, limiting the study's conclusiveness. Limitations in data accuracy and timely updates were acknowledged, suggesting a need for more current and comprehensive data sources. Despite this, the project established a transferable methodology applicable to diverse urban landscapes for identifying suitable sites for private educational institutions.

## File Description

README.md: Project description

Suitable-Sites-Analysis-for-Private-Schools-inToronto.pdf: Final report including analysis and results


## Tools and Technologies

PostgreSQL, PostGIS, QGIS

## Author

Amrinder Sehmbi

amrindersehmbi@outlook.com
