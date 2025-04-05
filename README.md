# Credit Risk Impact Analysis

### Project Overview

This project analyzes sovereign debt default probabilities under various economic conditions using historical global crisis data. The analysis focuses on understanding how factors such as inflation, exchange rates, and financial crises impact the likelihood of sovereign debt defaults, with special attention to extreme economic scenarios.

### Data Source

The analysis uses the "global_crisis_data" dataset, which contains historical information on various types of financial crises, sovereign defaults, inflation rates, exchange rates, and other economic indicators across multiple countries and time periods.

### Key Features

1. Data Cleaning and Preparation
- Standardizing column names
- Handling missing values
- Converting data types
- Creating composite indicators (e.g., financial_crisis)

2. Credit Risk Modeling
- Logistic regression model to predict default probability
- Feature importance analysis
- Model evaluation metrics

3. Risk Analysis Visualizations
- Feature impact plots
- 3D visualization of combined effects
- Risk segmentation analysis

4. Extreme Conditions Simulation
- Prediction of default probability under 95th percentile stress conditions
- Analysis of hyperinflation and currency crisis scenarios

### Methodology

1. Data Preparation Process
- The code cleans the original dataset by:

2. Standardizing column names
- Converting data types
- Creating composite indicators
- Handling missing values appropriately for different variable types

3. Model Development

The credit risk model:
- Uses logistic regression to predict default probabilities
- Identifies key factors influencing sovereign defaults
- Evaluates model performance with training/test split validation

### Risk Analysis Tools

The project includes functions for:

1. Visualizing how individual factors affect default probability
2. Creating 3D visualizations of multiple risk factors
3. Segmenting observations into risk categories
4. Simulating extreme economic conditions

### Key Findings

1. Financial crises are the strongest predictor of sovereign defaults
2. Extreme inflation appears particularly dangerous for debt sustainability
3. Exchange rate fluctuations have relatively minimal direct impact
4. The vast majority of historical observations fall into low risk categories
5. Even under 95th percentile stress conditions, default probability remains under 10%

### Future Enhancements

- Add political stability and institutional strength variables
- Implement more sophisticated machine learning models
- Create interactive dashboards for risk monitoring
- Incorporate time-series analysis for early warning indicators
- Expand analysis to include corporate debt defaults

### Source

[Global Crisis Dataset from Kaggle](https://www.kaggle.com/datasets/ayush12nagar/global-crisis)
