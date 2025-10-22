# Urban-Data-Analysis-Parks-Neighborhood-Quality-in-Pittsburgh-
# Pittsburgh Parks & Green Space Analysis

## Overview
This project analyzes the distribution of parks and green space across Pittsburgh neighborhoods using geospatial data analysis. The goal is to identify which neighborhoods have the highest ratio of park land to total land area, providing insights into urban green space accessibility.

## Key Findings
- **Squirrel Hill South** has the highest green space ratio at 60.9%
- **Hays** follows with 57.2% green space coverage
- Analysis reveals significant variation in park accessibility across Pittsburgh's 90 neighborhoods

## Technologies Used
- **Python**
- **pandas** - Data manipulation and analysis
- **geopandas** - Geospatial data processing
- **matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Data Sources
- [Pittsburgh Parks](https://data.wprdc.org/) - Western Pennsylvania Regional Data Center (WPRDC)
- [Pittsburgh Neighborhoods](https://data.wprdc.org/) - Western Pennsylvania Regional Data Center (WPRDC)

## Methodology
1. **Data Collection**: Retrieved park locations and neighborhood boundaries from WPRDC
2. **Spatial Analysis**: Used coordinate reference system (EPSG:32617 - UTM Zone 17N) for accurate area calculations
3. **Park Assignment**: Assigned each park to a single neighborhood using centroid-based spatial joins
4. **Ratio Calculation**: Computed green space ratio as (Total Park Area / Neighborhood Area) × 100

## Visualizations
The project includes two visualizations:
- **Choropleth Map**: Shows green space distribution across Pittsburgh neighborhoods
- **Horizontal Bar Chart**: Ranks all neighborhoods by green space percentage
