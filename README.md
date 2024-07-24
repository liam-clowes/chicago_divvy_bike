### chicago_divvy_bike
# Chartered Territories: Testing the boundaries of data protection in geospatial datasets 
## (Capstone Project, Spiced Academy 2024)

-- Add TOC -- 

### Project Overview

This project aims to uncover insights into the habits of Chicago's Divvy bike-share users during the busiest months of the year — July, August, and September (Q3) — spanning the years 2020 to 2023. Through a comprehensive analysis of the Divvy dataset, the project will identify user trends, provide data-driven recommendations to expand existing Divvy bike-share schemes, and explore the boundaries of data privacy in the context of anonymised geospatial datasets.

### Data Sources

- **Main Source**: the primary dataset used for this analysis is from [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html) (looking specifically at the months of July, August, and September)
- **Additional sources**: 'boundaries_neighborhoods.geojson' from the [Chicago Data Portal](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Neighborhoods/bbvz-uum9) (used primarily on geospatial visualisations)

#### Columns in the dataset:

- ride_id (ride id)
- rideable_type (electric or classic)
- started_at (time started)
- ended_at (time ended)
- start_station_name (station name - start)
- start_station_id (station id - start)
- end_station_name (station name - end)
- end_station_id (station id - end)
- start_lat (start latitude)
- start_lng (start longitude)
- end_lat (end latitude)
- end_lng (end longitude)
- member_casual (member, single ride, day pass)

### Tools

- **Jupyter Notebook**: For interactive data analysis and visualisation.
- **Python**: The core programming language for the project.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning and data modelling.
- **NumPy**: For numerical operations.
- **Datetime**: For handling date and time data.
- **Category Encoders**: For encoding categorical variables.
- **Geopandas**: For working with geospatial data.
- **Folium**: For creating interactive maps.
- **Matplotlib & Seaborn**: For data visualisation.
- **Plotly**: For interactive graphing.
- **Geopy**: For geocoding and geographical operations.
- **Google Maps**: For cross-referencing locations and identifying buildings at each station/on each route.

### Data Cleaning & Preparation

In the initial data preparation phase, I performed the following tasks:
1. Data loading and inspection
2. Identifying busiest quarter of each year
3. Handling missing/null values
4. Handling outliers
5. Data cleaning and formatting

### Exploratory Data Analysis 

EDA involved exploring the Divvy dataset to answer the following key questions: 

- What trends can we identify within pre-existing user groups (members vs. casual users, electric users vs. docked/classic users)?
- Is it possible to apply clustering on the data to identify new/organic user groups?
- Can I identify potential target businesses for bike-share schemes or campaigns by examining the top stations and routes and their surrounding areas?
- Is it possible to track user habits and potentially identify individual users by combining existing anonymized data with open-source tools like Google Maps and company websites?
- How can these findings be applied to other geospatial datasets?

### Data Analysis

```
insert some interesting code/features worked with
```


