# Crime_Indicator_Geospatial_Toronto

# Toronto Crime Data Analysis

This repository contains a comprehensive analysis of crime data from Toronto, focusing on identifying spatial and temporal patterns to derive actionable insights for urban planning and law enforcement strategies.

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Data Overview and Processing](#data-overview-and-processing)
- [Analysis Overview](#analysis-overview)
  - [Spatial and Temporal Crime Maps](#spatial-and-temporal-crime-maps)
  - [Crime Type Analysis](#crime-type-analysis)
  - [Region-Wise Clusters](#region-wise-clusters)
  - [Temporal Analysis](#temporal-analysis)
- [Statistical Analysis](#statistical-analysis)
  - [Regression Analysis](#regression-analysis)
  - [Spatial Autocorrelation Analysis](#spatial-autocorrelation-analysis)
- [Conclusion](#conclusion)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [Contributions](#contributions)

## Introduction

This project aims to analyze crime data from Toronto to uncover spatial and temporal trends, providing insights for targeted interventions, enhanced urban planning, and public safety improvements. The dataset includes details like event identifiers, report dates, occurrence dates, offense types, geographical coordinates, and neighborhood contexts.

## Objective

The key objectives of this analysis are:

1. Analyzing the spatial and temporal distribution of crime incidents in Toronto.
2. Identifying patterns and hotspots for various offense types.
3. Providing insights to inform urban planning and public safety strategies.

## Data Overview and Processing

The dataset includes:

- Event IDs
- Report dates
- Occurrence dates
- Offense types
- Geographical coordinates (latitude and longitude)

Key preprocessing steps included:

1. Converting the CSV file into a GeoDataFrame for spatial analysis.
2. Incorporating neighborhood boundary shapefiles to contextualize crime locations.
3. Applying statistical and geospatial techniques to analyze and visualize patterns effectively.

## Analysis Overview

### Spatial and Temporal Crime Maps

- Crime incidents are concentrated in downtown Toronto due to high population density and commercial activity.
- Suburban areas show dispersed patterns influenced by socio-economic and demographic factors.

### Crime Type Analysis

- Different offense types, such as assaults, thefts, robberies, and break-and-enter incidents, exhibit unique spatial patterns.
- Crime maps categorized by offense type and Major Crime Indicator (MCI) categories reveal targeted intervention areas.

### Region-Wise Clusters

- Central Toronto emerges as a consistent hotspot for crimes like assaults and robberies.
- Suburban areas display dispersed crime patterns, reflecting lower population density.

### Temporal Analysis

- Assault incidents peak between 6 PM and 2 AM, often in nightlife and entertainment districts.
- Proportional symbol maps and heatmaps provide visual insights into crime volumes and densities across neighborhoods.

## Statistical Analysis

### Regression Analysis

- Regression analysis reveals a significant relationship between the hour of the day and assaults, with an R-squared value of 0.650.
- Temporal trends highlight the need for strategic resource allocation during peak hours.

### Spatial Autocorrelation Analysis

- Moran's I test confirms clustering of assaults, indicating non-random spatial distribution.
- Insights from spatial autocorrelation can inform urban planning and law enforcement strategies.

## Conclusion

This analysis highlights:

1. Spatial clustering of crime in specific neighborhoods.
2. Temporal patterns emphasizing peak crime hours.
3. Actionable insights for targeted policing and urban planning.

Future work could expand to include socio-economic data and broader crime categories to enhance understanding of crime dynamics in Toronto.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/toronto-crime-analysis.git
   ```
2. Install dependencies (see below).
3. Run the analysis notebooks and scripts to generate visualizations and insights.

## Dependencies

- Python 3.8+
- pandas
- geopandas
- matplotlib
- seaborn
- scikit-learn
- folium

Install dependencies using pip:
```bash
pip install pandas geopandas matplotlib seaborn scikit-learn folium
```

## Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

For questions or feedback, feel free to open an issue or contact the maintainer.

