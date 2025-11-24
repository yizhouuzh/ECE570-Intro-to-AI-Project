# MULTI-TASK SELF-SUPERVISED LEARNING FOR HUMAN ACTIVITY RECOGNITION

## Description

This project investigates the effectiveness of Multi-Task Self-Supervised Learning (SSL) for Human Activity Recognition (HAR) using the OPPORTUNITY Dataset. The central goal is to determine if a multi-task SSL framework can learn more robust sensor representations from unlabeled data.

## Prerequisites

* **Python**: Version 3.8 or higher
* **Data**: The original OPPORTUNITY Dataset files can be downloaded from https://archive.ics.uci.edu/dataset/226/opportunity+activity+recognition
* **Jupyter Notebook**

## Installation
* pandas>=2.0.0
* numpy>=1.20.0
* scipy>=1.10.0
* matplotlib>=3.5.0
* seaborn>=0.12.0
* scikit-learn>=1.0.0
* xgboost>=1.7.0
* torch>=2.0.0
* torchvision>=0.15.0
* tqdm>=4.64.0
* mlxtend>=0.23.0
* optuna>=3.0.0
* Pillow>=9.0.0

## Notebook Guide

1. preprocessing.ipynb: This notebook executes all initial data preparation steps, including data cleaning, imputation, and standardization.

2. EDA.ipynb: A brief notebook contains exploratory data analysis of the data

3. XGBoost.ipynb: This notebook employs XGBoost model to conduct HAR.

4. SSL.ipynb: This notebook employs Self-Supervised Learning model.
