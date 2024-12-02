# Energy-Efficiency-Statistical-Analysis

Project Proposal: Estimating heating and cooling loads based on building characteristics

## 1. Dataset Description
Dataset Link: https://archive.ics.uci.edu/dataset/242/energy+efficiency

The dataset for this analysis comes from the UCI Machine Learning Repository and contains housing price data from a metropolitan area. The dataset has 8 variables, 2 target values, and
768 observations with no missing values. The data was collected from performing energy analysis using 12 different building shapes simulated in Ecotect. The target variables are heating load (HL) and cooling load (CL), representing the energy requirements for maintaining thermal comfort within buildings.

<ins>Variables:</ins>

**X1** - Relative Compactness: A measure of the building’s shape efficiency <br />
**X2** - Surface Area: The total surface area of the building <br />
**X3** - Wall Area: The area of the walls, contributing to heat transfer <br />
**X4** - Roof Area: The area of the roof, affecting thermal insulation <br />
**X5** - Overall Height: Building height, impacting air flow and heat transfer <br />
**X6** - Orientation: Cardinal direction of the buildings facade <br />
**X7**- Glazing Area: Total window area, influencing natural light and insulation <br />
**X8** - Glazing Area Distribution: Spread of window area on each facade <br />

**Y1** (Response Variable) - Heating Load: Energy required for Heating. <br />
**Y2** (Response Variable) - Cooling Load: Energy required for Cooling.

## 2. Objectives

The main objective of this project is to analyze the dataset in terms of the variables in order to develop a predictive model that will depict the most efficient heating and cooling loads based on the building characteristics. Identify and interpret the influence of each building feature on energy efficiency, providing insights that can inform sustainable design practices. Optimize model performance by experimenting with different regression techniques and feature selection methods.

## 3. Plan of Analysis

First, explore the dataset to determine whether the dataset is normally distributed or not. Furthermore, evaluate regression models by splitting the data into training, test sets, and computing prediction errors in order to assess model performance. Utilizing the following:

- Multiple Linear Regression
- Stepwise Logistic Regression
- Decision Tree Regression
- Correlation Matrix

For data analysis to find the accuracy within each model, we will use:

- Mean Absolute Error (MAE)
- RMSE (Root Mean Squared Error)

Given that there are 2 response targets, separate models will be ran in order to compare r<sup>2</sup> and prediction errors.
