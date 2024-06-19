# Londoncrimeanalysis2020
# Introduction
In this article, we explore crime data in London for January 2020, providing valuable insights into crime patterns and types. This analysis involves data cleaning, feature engineering, and visualizations to identify key trends and areas with high crime rates. The goal is to inform public safety strategies and provide residents with data-driven insights for their safety.

## Data Exploration and Cleaning
Initial Overview

The dataset contains 90,979 entries and 12 features. Initial inspection revealed several columns that do not contribute significantly to the analysis, which were subsequently dropped: "Crime ID", "Context", "Falls within", "Reported by", and "LSOA code".

## Data Summary

A detailed examination identified missing values and duplicates. Notably, "Longitude" and "Latitude" had less than 1% missing values, while the "Last outcome category" had 19% missing values. Missing geographical coordinates were dropped, and the "Last outcome category" was imputed with its mode.

## Data Type Reassignment and Column Renaming

The "Month" column was converted to datetime format and renamed to "Date". Additional columns "month" and "year" were created for more granular temporal analysis. The column "LSOA name" was renamed to "LSOA_name", "Crime type" to "Crime_type", and "Last outcome category" to "Last_outcome_category".

## Data Visualization
Geographical Distribution of Crimes

A scatter plot of crime locations overlaid on a map of the United Kingdom showed a high concentration of crimes in London.

## Univariate Analysis

The analysis of crime types revealed that certain types of crimes were more prevalent:

## Key findings include:

Top Crime Locations: Westminster, Camden, Tower Hamlets, Southwark, and Lambeth were identified as areas with the highest crime rates.
Crime Type Distribution in Key Areas: Detailed breakdowns of crime types for these locations highlighted the specific challenges each area faces.
Crime Distribution in High-Crime Areas
Westminster

Westminster showed a high incidence of theft-related crimes.

### Camden

Camden's crime profile was similar, with theft being the most common crime type.

### Tower Hamlets

Tower Hamlets also had a high rate of theft-related crimes, along with significant occurrences of violent crimes.

### Southwark

Southwark's crime distribution highlighted a need for targeted intervention in theft and violence reduction.

### Lambeth

Lambeth's crime analysis indicated theft and violence as major issues.

### Crime Type Distribution
The pie charts for the top crime areas visually represent the distribution of crime types:

### Pivot Table Analysis
A pivot table excluding 'Other crime' and 'Other theft' provided a clear view of meaningful crime statistics across boroughs.

### Crime Outcomes
The relationship between crime types and their outcomes was analyzed, revealing interesting correlations. A heatmap illustrated these correlations effectively:

## Conclusion
This detailed analysis of London’s crime data for January 2020 provides critical insights:

* High-Crime Areas: Westminster, Camden, Tower Hamlets, Southwark, and Lambeth require focused crime reduction efforts.
* Prevalent Crime Types: Theft and violence are the most common crime types across high-crime areas.
* Geographical Concentration: Crimes are heavily concentrated in London, necessitating targeted public safety strategies.
* Temporal Insights: Monthly and yearly breakdowns aid in understanding crime trends over time.
* Data-Driven Decision Making: The insights enable authorities to allocate resources effectively and design targeted interventions.
* Public Awareness: Residents can use this information to make informed decisions about their safety and residential choices.
This comprehensive analysis lays the groundwork for future research and ongoing monitoring to enhance public safety and reduce crime in London. 
