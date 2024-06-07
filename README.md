# Stock-Market-Price-Prediction

## Overview

* The price of the [S&P500](https://www.investing.com/indices/us-spx-500) Stock Market Index is predicted using [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) in this project.
* This repository contains the code and resources of this Stock Market Index price prediction project.

## Steps

* Downloading data using the yfinance package
* Cleaning and visualizing stock market data
* Setting up a target for machine learning
* Creating an initial machine-learning model 
* Building a backtesting engine to more accurately measure accuracy
* Adding additional predictors to the model
* Improving the accuracy of the model

## Code

You can find the code for this project [here](https://github.com/dataquestio/project-walkthroughs/tree/master/sp_500).

File overview:

* `market_prediction.ipynb` - a Jupyter notebook that contains all of the code.

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * yfinance
    * scikit-learn

## Data

We'll download all of the data during the project, using the `yfinance` package.
