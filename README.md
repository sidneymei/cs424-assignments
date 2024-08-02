# CS424 Traffic Crash Analysis Project

This repository contains parts of a multi-part project for CS424 (Fall 2023) - Visualization & Visual Analytics. Our group, The Tree Friends, analyzed the "[Traffic Crashes - Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if)" dataset from the City of Chicago to gain insights into traffic accidents within the city limits.

## Project Parts

1. [Part 1: Visualization Sketching](#part-1-visualization-sketching)
2. [Part 2: Exploratory Data Analysis](#part-2-exploratory-data-analysis)
3. [Part 3: Interactive Visualizations](#part-3-interactive-visualizations)
4. [Part 4: Final Visualization Website](#part-4-final-visualization-website)

## Part 1: Visualization Sketching

**Files**: No code files (consisted of hand-drawn sketches)

In this initial phase, we:
- Described the dataset and its potential uses
- Formulated domain questions to guide our analysis
- Created task abstractions using Brehmer and Munzner's typology
- Sketched various visualization ideas for each domain question

Key visualizations sketched included calendar heatmaps, stacked area charts, geospatial heatmaps, and grouped bar charts.

## Part 2: Exploratory Data Analysis

**Files**:
- `2_1.ipynb`: Jupyter notebook for data loading, profiling, and cleansing
- `2_2.ipynb`: Jupyter notebook for initial visualizations
- `df_unique_values.json`: JSON file containing unique values from the dataset

For this part, we:
- Loaded, profiled, and cleansed the data
- Created initial visualizations based on our sketches
- Implemented a calendar heatmap, stacked area chart, double-time bar graph, grouped bar chart, choropleth map, and heatmap

Key insights:
- May had the most crashes overall
- Crash peaks were observed in 2018, 2019, and 2020, with a dip during COVID-19
- More crashes occurred during the day than at night
- Most injuries occurred under normal conditions
- Downtown areas showed higher crash frequencies

## Part 3: Interactive Visualizations

**File**: `3.ipynb`: Jupyter notebook containing all interactive visualizations

In this phase, we created more advanced, interactive visualizations:
- A choropleth map combined with a bar graph to show crashes per police beat and injuries based on speed limit
- A heatmap and bubble chart showing the relationship between most severe injury and primary contributory cause
- Parallel coordinates plot and point chart with jittering for insights into day of week and crash hour
- Donut chart and line chart for weather condition distribution and crashes over time
- A bubble map showing binned crash locations throughout the city

These visualizations allowed for more in-depth exploration of the data through user interaction.

## Part 4: Final Visualization Website

**Repository**: [website-thetreefriends](https://github.com/sidneymei/website-thetreefriends)

The culmination of our project is a comprehensive visualization website. Key features include:
- Interactive calendar heatmap
- Choropleth map with linked bar graph
- Dot plot and multiple line graph for temporal insights
- Bubble map for spatial distribution of crashes

We performed additional data transformations, including:
- Removal of documents with geocoordinate points outside city boundaries
- Omission of certain features and documents with missing values
- Feature engineering for each visualization

Our visualizations use various encodings such as area, color, position, and size to represent different aspects of the data.

Visit our [live website](https://sidneymei.github.io/website-thetreefriends) to explore the visualizations.