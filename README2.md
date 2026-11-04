NYC Yellow Taxi Big Data Analytics Project

Project Overview

This project applies Big Data Analytics techniques to New York City Yellow Taxi trip records for January 2025. It uses Apache Spark and PySpark to process, clean and analyse large-scale transportation data, develop a machine learning model and demonstrate predictive analytics using Structured Streaming.

Project Objectives

Process and clean large-scale taxi trip records.

Analyse transportation patterns and trip characteristics.

Perform feature engineering.

Develop a Random Forest Regression model to predict taxi trip durations.

Evaluate model performance using RMSE, MAE and R-squared.

Integrate the trained model with Spark Structured Streaming.

Dataset

Source: New York City Taxi and Limousine Commission (TLC).

Dataset: January 2025 Yellow Taxi Trip Records.

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Technologies Used

Python

Apache Spark

PySpark

Jupyter Notebook

Spark SQL

Spark MLlib

Random Forest Regression

Structured Streaming

Pandas and Matplotlib

Model Evaluation Results

Original test evaluation:

RMSE: 6.73 minutes

MAE: 4.28 minutes

R-squared: 0.6451

Streaming evaluation:

RMSE: 5.15 minutes

MAE: 4.13 minutes

R-squared: 0.6916

The streaming evaluation used a separate set of records and should not be interpreted as proof that the model improved.

Project Implementation

The Jupyter Notebook contains the complete project implementation, including:

Spark configuration and data loading.

Dataset understanding and exploration.

Data cleaning and validation.

Exploratory data analysis.

Feature engineering.

Performance analysis.

Spark SQL analysis.

Random Forest model development.

Model evaluation and feature importance.

Model saving and loading.

Structured Streaming implementation.

Streaming model predictions.

Project Purpose

The project demonstrates how Big Data technologies and machine learning can support
transportation data analysis, journey-duration estimation and evidence-based transportation planning.
