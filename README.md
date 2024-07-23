### chicago_divvy_bike
# Chartered Territories: Testing the boundaries of data protection in geospatial datasets 
## (Capstone Project, Spiced Academy 2024)

-- Add TOC -- 

### Project Overview

This project aims to uncover insights into the habits of Chicago's Divvy bike-share users during the busiest months of the year — June, July, and August (Q3) — spanning the years 2020 to 2023. Through a comprehensive analysis of the Divvy dataset, the project will identify user trends, provide data-driven recommendations to expand existing Divvy bike-share schemes, and explore the boundaries of data privacy in the context of anonymised geospatial datasets.

### Data Sources

- **Main Source**: the primary dataset used for this analysts is from [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html) (looking specifically at June, July & August)
- **Additional sources**: 'boundaries_neighborhoods.geojson' from the [Chicago Data Portal](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Neighborhoods/bbvz-uum9) (used primarily on geospatial visualisations)

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

EDA involved exploring the Divvy dataset to answer my key questions: 

- What sort of trends can be identified within each user group (members vs. casual, electric vs. docked/classic)?
- Is it possible to do clustering within user groups?
- By looking at the top stations/routes, am I able to identify possible target businesses in surrounding areas for bike-share schemes/campaigns?
- Using the available data from the dataset and other open sources (e.g. Google Maps and business websites), is it possible to track the habits of, and potentially identify, individual users?
- How can this information be applies to other geospatial datasets?

Columns in the dataset:
ride_id (ride id)
rideable_type (electric or classic)
started_at (time started)
ended_at (time ended)
start_station_name (station name - start)
end_station_name (station name - end)
start_lat (start latitude)
start_lng (start longitude)
end_lat (end latitude)
end_lng (end longitude)
member_casual (member, single ride, day pass)


### Data Analysis

```
insert some interesting code/features worked with
```


