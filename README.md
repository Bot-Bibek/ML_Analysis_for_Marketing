## ML_Analysis_for_Marketing

## Abstract

This project focuses on applying Advanced Machine Learning techniques to retail sales analysis using three years of historical sales data from 45 stores across different regions. Each store consists of multiple departments, providing a comprehensive dataset for exploring sales patterns and trends.

The project aims to analyze retail sales data, uncover meaningful insights, and explore machine learning approaches that can support data-driven decision-making in the retail industry.

## Introduction

Retail businesses often face the challenge of making strategic decisions with limited historical data. Sales patterns can fluctuate significantly during holidays, special events, discounts, and promotional campaigns. Understanding these fluctuations is essential for identifying opportunities, managing resources, and improving business performance.

Holiday periods, in particular, can lead to significant increases in sales. At the same time, markdowns and promotional strategies may influence customer purchasing behavior and overall revenue. Analyzing these factors helps businesses understand how different departments respond to seasonal events and strategic pricing decisions.

The primary goal of this project is to apply advanced machine learning techniques to retail sales data to predict departmental sales, evaluate the impact of markdowns, and generate actionable business recommendations.

### Project Objectives

The main objectives of this project are:

1. **Department-Wide Sales Prediction:** Predict sales for individual departments across different retail stores.
2. **Markdown Impact Analysis:** Model and evaluate the effects of markdowns on sales during holiday weeks.
3. **Marketing Recommendations:** Develop data-driven marketing recommendations based on analytical insights, prioritizing strategies with the greatest potential business impact.

## Materials and Methods

This project explores retail sales analysis and forecasting using historical sales data. It applies time-series analysis and multiple machine learning techniques to understand sales patterns, predict future departmental sales, and evaluate the impact of markdowns on retail performance.

The analysis includes autocorrelation techniques to identify time-lag relationships in sales data and appropriate data transformations to capture temporal dependencies. Different machine learning models are then developed and evaluated to forecast weekly department-level sales.

Additionally, neural network models are used to investigate how markdowns influence sales during holiday and regular weeks. Based on the analytical findings, data-driven marketing strategies are proposed for selected retail departments.

### Project Workflow

The project consists of the following stages:

#### 1. Data Preparation and Setup
- Import required Python libraries and define auxiliary functions.
- Download and prepare the retail dataset.
- Perform initial data cleaning and preprocessing.

#### 2. Department-Wide Sales Prediction

- **Preliminary Data Analysis:** Explore sales distributions, trends, and patterns.
- **Dataset Creation:** Prepare time-series datasets for model training.
- **Data Normalization:** Normalize features to improve model performance.
- **Linear Regression:** Establish a baseline forecasting model.
- **Backpropagation Neural Network (BPNN):** Apply neural networks to capture nonlinear sales relationships.
- **Long Short-Term Memory (LSTM):** Use recurrent neural networks to model temporal dependencies and forecast weekly sales.

#### 3. Modeling the Effects of Markdowns on Holiday Weeks

- **Preliminary Analysis:** Investigate markdowns and their relationship with sales during holiday and regular weeks.
- **Linear Regression:** Analyze the relationship between markdowns and sales.
- **Backpropagation Neural Network:** Model potentially nonlinear relationships between markdowns and sales.
- **Sensitivity Analysis:** Evaluate how changes in markdown strategies influence sales outcomes.

#### 4. Department-Level Recommendations

Develop data-driven marketing and sales strategy recommendations for a selected department based on the insights obtained from the analysis.

#### 5. Final Tasks

- **Subtask 1 – Sensitivity Function:** Develop a function to perform sensitivity analysis.
- **Subtask 2 – Department Sensitivity:** Evaluate the sensitivity of an individual department to markdown changes.
- **Subtask 3 – Multi-Department Sensitivity:** Extend the sensitivity analysis to 10 different departments.

### Dataset and Data Source

The dataset used in this project is the [Retail Dataset from Kaggle](https://www.kaggle.com/datasets/manjeetsingh/retaildataset).

It contains historical retail sales information from 45 stores, covering multiple departments and approximately three years of sales activity.

**Dataset License:** CC BY-IGO (as specified in the original dataset documentation).
