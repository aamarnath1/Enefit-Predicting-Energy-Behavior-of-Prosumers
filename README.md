# DSCI-445 Final Project: Predict Energy Behavior of Prosumers

### Authors: Arya Amarnath, Ronnie Delgado, Lucas Pacheco

## Overview
This repository contains all the code and datasets for our project on predicting the energy behavior of prosumers. The goal is to accurately forecast energy consumption and production patterns for Estonian prosumers using machine learning techniques.

## Project Structure
- **[Final_Project_Presentation.qmd](Final-project-presentation.qmd)**: Quarto Markdown file detailing our data preprocessing, exploratory data analysis, and modeling.
- **[Final_Project_Presentation.html](Final-project-presentation.html)**: HTML file of the final presentation.
- **Data**: Directory containing the datasets used in the project.
  - Within 'predict energy behavior of prosumers'
- **Images**: Contains visualizations and figures used in the project.
  - `eesti-energia-logo.png`
  - `enefit-solar-roof.png`
  - `Enerfit-kaggle-image.png`
  - `3-Learning-curves-for-electricity-prices.png`
  - `CV_TreePlot.png`
  - `gam_plot.png`
  - `xgboost_imp.png`

## Research Methodology
Our project involves:
1. **Data Cleaning**: Processing and organizing the energy consumption, production data, market prices, and weather data.
2. **Exploratory Data Analysis (EDA)**: Identifying key trends and patterns in the data using Pandas and visualization libraries such as Matplotlib and Seaborn.
3. **Model Development**: Implementing linear, GAM, Decision Trees, and XGBoost to predict energy behavior, including feature engineering and model validation.

## Key Findings
- Our XGBoost model accurately forecasts Estonian prosumers' energy consumption and production patterns with a RMSE of 147.4 and MSE of 56.6
- Addressing energy imbalance helps in efficient energy management and planning.

## Future Work
- Enhance prediction accuracy by including more variables.
- Integrate the model into a real-time energy management system for continuous monitoring and forecasting.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
