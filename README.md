# Geospatial Data Analysis

## Project Overview

This project analyzes regional and geospatial data to identify areas with potential market opportunities based on search demand, competition, lead conversion rates, and acquisition costs.

The analysis uses the dataset provided for the Workora Geospatial Data Analysis task.

## Objectives

- Analyze regional search demand
- Examine competition across regions
- Compare lead conversion rates
- Analyze acquisition costs
- Identify high-potential underserved regions
- Visualize regional opportunities geographically

## Dataset

The dataset contains regional information including:

- Region ID
- City
- State
- Latitude
- Longitude
- Population Segment
- Monthly Search Demand
- Existing Competitors
- Median Annual Income
- Lead Conversion Rate
- Estimated Acquisition Cost

## Analysis Performed

- Data cleaning and validation
- Regional demand analysis
- State-level aggregation
- Competition analysis
- Demand-per-competitor analysis
- Opportunity scoring
- Geographic visualization using Folium
- Identification of three high-potential regions

## Key Metric

An Opportunity Score was created using search demand, lead conversion rate, and existing competition.

The score is a prioritization metric and should not be interpreted as direct revenue or profit.

## Visualizations

The project includes:

- Search demand by state
- Demand vs existing competition
- Top 3 opportunity regions
- Interactive geographic opportunity map

## Interactive Map

The interactive map is available in:

`geospatial_opportunity_map.html`

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- Jupyter Notebook

## Deliverables

- `geospatial_analysis.ipynb`
- `geospatial_opportunity_map.html`
- `README.md`
