# TCS iON RIO-125 Internship: Sales Forecasting System

## Project Overview
This repository contains the code and dataset for the TCS iON RIO-125 Internship project titled **"Forecasting System - Project Demand of Products at a Retail Outlet Based on Historical Data"**. The project was completed as part of the TCS iON Remote Internship program (January 20, 2025, to February 4, 2025, covering the first 15 days). The objective is to build a forecasting system to predict product demand at a retail outlet using historical sales data.

The project involves:
- Creating and preprocessing a dataset (Milestone 1: Day 5).
- Performing exploratory data analysis (EDA) to identify sales patterns.
- Building and evaluating forecasting models, including moving average, STL decomposition, SARIMA, and Prophet (Milestone 2: Day 15).
- Achieving an RMSE of 84,342 with Prophet, meeting the target of below 100,000 by Day 15.

This work was initially developed using Kaggle notebooks and later uploaded to GitHub for submission to TCS.

## Repository Contents
- **`forecasting-system-Internship-Project.ipynb`**: The main Jupyter Notebook containing all code for the project, including:
  - Data loading and preprocessing (e.g., merging datasets, handling missing values).
  - Exploratory data analysis (e.g., visualizing sales trends, holiday impacts).
  - Modeling (moving average, STL, SARIMA, Prophet) and evaluation (RMSE calculations).
  - Predictions for the test period (2017-07-16 to 2017-08-15).
  - Note: The notebook may not render directly on GitHub due to its size/complexity. View it on nbviewer: [https://nbviewer.jupyter.org/github/Prathmesh597/tcs-internship-sales-forecasting/blob/main/forecasting-system-Internship-Project.ipynb](https://nbviewer.jupyter.org/github/Prathmesh597/tcs-internship-sales-forecasting/blob/main/forecasting-system-Internship-Project.ipynb).
- **Dataset Files**:
  - `holidays_events.csv` (22,309 bytes): Holiday events data.
  - `oil.csv` (20,580 bytes): Daily oil prices.
  - `stores.csv` (1,387 bytes): Store details.
  - `test.csv` (1,022,269 bytes): Test data for predictions.
  - `transactions.csv` (1,552,637 bytes): Transaction data.
  - `sample_submission.csv` (342,153 bytes): Sample submission format.
  - Note: `train.csv` (121,800,373 bytes) exceeds GitHub’s 100 MB file size limit and is not uploaded. Download it from Kaggle (see below).

## Dataset Source
The dataset used in this project is the "store-sales-time-series-forecasting" dataset from Kaggle, available at:  
[https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)  
To run the notebook, download `train.csv` from the Kaggle link and place it in the repository directory alongside the other dataset files.

## Prerequisites
To run the code, ensure you have the following installed:
- Python 3.10 or higher
- Jupyter Notebook
- Required libraries: Install them using the following command:
  ```bash
  pip install pandas matplotlib prophet statsmodels
