**California Housing Price Prediction — Linear Regression from Scratch**

This project demonstrates how to predict California housing prices using Multiple Linear Regression, implemented entirely from scratch — without using libraries like scikit-learn.

The goal is to understand the mathematical foundation and implementation logic behind regression models, focusing on the step-by-step development of a predictive model using only NumPy and Pandas.

**Project Overview**

The California Housing dataset contains various features related to housing conditions in different districts of California. Each row represents data for one district, including:

  MedInc – Median income in the area

  HouseAge – Median age of houses

  AveRooms – Average number of rooms per household

  AveBedrms – Average number of bedrooms per household

  Population – Total population of the area

  AveOccup – Average household size

  Latitude & Longitude – Geographic coordinates

Using these features, the model predicts the median house value (Price).

**What’s Implemented**

  Manual implementation of Gradient Descent algorithm

  Cost Function (MSE) to measure model error

  Feature Normalization for better convergence

  Training loop with cost tracking across iterations

  Visualization of cost reduction using Matplotlib and Plotly

  Model parameter updates using matrix operations

**Tools & Libraries Used**

  NumPy – for matrix operations and mathematical computations

  Pandas – for data handling and preprocessing
  
  Matplotlib & Plotly – for visualizing trends and cost function

  (No sklearn used!)

**Objective**

  To understand how Linear Regression works internally by coding every step — from reading data, normalizing features, defining cost functions, to performing optimization using gradient descent.

**Key Learning Outcomes**

  Build a complete regression model without any ML library shortcuts

  Understand how theta values (weights) are optimized

  Observe the relationship between learning rate and cost convergence

  Gain deeper insight into the mathematical intuition behind linear regression
