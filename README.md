


# Bike-Sharing Demand Prediction App

## Project Overview
This repository contains the R Shiny application for predicting bike-sharing demand based on weather forecast data. The application provides an interactive dashboard to visualize the demand in various major cities. The purpose is to assist city planners and bike-sharing companies in managing resources more efficiently.

**Live App**: [Bike-Sharing Demand Prediction App](https://aarav12357.shinyapps.io/BikeSharingDemandPredictionAarav/)

## Objectives
- **Demand Prediction**: Predict hourly bike-sharing demand using weather data.
- **Interactive Visualization**: Utilize R Shiny and Leaflet to provide interactive visual representations of predicted demands.
- **City-Specific Insights**: Offer tailored predictions for New York, Paris, Suzhou, and London, with plans to expand to more cities.

## Data Sources
The application uses real-time weather data from the OpenWeather API and historical bike-sharing usage patterns to make predictions.

## Tools and Technologies
- **R**: Primary programming language for server-side logic.
- **R Shiny**: Framework for developing interactive web applications directly from R.
- **Leaflet**: For interactive maps.
- **Google Colab**: Notebooks for exploratory data analysis and model development.





## Repository Contents

- `model_prediction.R`: Contains the logic for fetching weather data and predicting demand.
- `ui.R` and `server.R`: UI and server logic for the Shiny application.

## Course Modules and Notebooks
Detailed analysis and methodology are documented in these Jupyter notebooks hosted on Google Colab:

### Data Collection
- [Module 1-1 Data Collection R](https://colab.research.google.com/drive/1YENwSXSXZclcMw9Wu8bGPufv7kws2PW6)
- [Module 1-2 Data Collection R](https://colab.research.google.com/drive/1Jyx-weafNdiqivVt-o3clHXQl9jTTu8R)

### Data Wrangling
- [Module 2-1 Data Wrangling R](https://colab.research.google.com/drive/1kZx8vOPXSLElmVLXnzZpwm_FP9sN7nYk)
- [Module 2-2 Data wrangling with dplyr](https://colab.research.google.com/drive/1YiNQiUmxhe-hIWpKz-rJ2Su8kySPDSy5)

### Exploratory Data Analysis
- [Module 3-1 Exploratory Data Analysis R](https://colab.research.google.com/drive/1URgZjgIHB0RXnWiplzeHT3lolk2q5ABL)
- [Module 3-2 Data Visualization R](https://colab.research.google.com/drive/1cQDj_wL4WXacWk4IzXvmwlD0MMcJ5s2t)

### Statistical Analysis
- [Module 4: Statistical Analysis](https://colab.research.google.com/drive/1_aIJjk3zmNS8d59SKzmPrSZXNgGLie4U)

### R Studio Code Setup
- [R Studio Code](https://colab.research.google.com/drive/1bmdYwGDfRGHGGb6hTDaW_cwbvatK1W6J#scrollTo=q_iJpfekXebZ)

## Presentation
A detailed PDF presentation explaining all the SQL queries performed on the data and the steps to get the Shiny app running in RStudio is included in the repository. This document is essential for understanding the backend operations and setup procedures.
