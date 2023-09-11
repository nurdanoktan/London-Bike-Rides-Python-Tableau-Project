# London-Bike-Rides-Python-Tableau-Project

![image](https://github.com/nurdanoktan/London-Bike-Rides-Python-Tableau-Project/assets/112075689/11601855-3fe2-47d2-8f68-9bf78a7f3d50)

**[Explore the Dashboard](https://public.tableau.com/app/profile/nurdan.oktan/viz/LondonBikeRidesProject_16926511039280/Dashboard1)**

This repository contains Python code and Tableau visualizations for analyzing and visualizing the London bike rides dataset. The [Kaggle london bike sharing dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) is gathered using Kaggle API and preproccesed using Python and Tableau is used to create an interactive dashboard.

## Data Cleaning

The dataset underwent the following data cleaning steps in Python using pandas:

- **Column Renaming**: Columns were renamed to provide more descriptive labels.
- **Humidity values transformation**: Humidity values are changed to percentage.
- **Weather Column Transformation**: The weather column was transformed from representative numbers to actual written weather conditions.

## Overview

This project aims to analyze and visualize London bike rides data using Python and Tableau. The key features and visualizations include:

1. **Average Moving Trends**: A line graph is available that shows the average moving trends over user-defined date ranges. Users can interact with the graph by dragging and holding to select specific periods.

2. **Total Bike Rides**: Users can specify date ranges to view the total number of bike rides within those date ranges.

3. **Temperature vs. Wind Speed Heatmap**: A heatmap is provided that compares the number of bike rides against temperature and wind speed. This heatmap allows users to hover over data points for additional details. It includes two charts: one for ride numbers by weather condition and another for ride numbers by the time of day.

## Project Structure

The project structure is organized as follows:

- `london-bike-sharing-dataset.zip`: Contains the original dataset gathered from Kaggle API.
- `London_bike_rides_data_cleaning.ipynb`: Includes Jupyter Notebook file for data preprocessing and analysis.
- `README.md`: This README file.
