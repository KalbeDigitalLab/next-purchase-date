# Next Purchase Date Prediction

## Description

This repository contains codes for the Next Purchase Date task utilizing a machine learning approach. We use three simple machine learning models: **Linear Regression**, **Random Forest Regressor**, and **XGBoost Regressor**. Those models are trained with each user-item transaction data, so each interaction that a user buys an item will have a separate model from the others. This separation has proved to get a better result than the model with all interactions because the model could only learn specifically about each behavior. 

Because of the large number of combinations between unique users and items, we only develop several models that align with some of our business scenario use cases. We separate each use case into different notebooks. 

## Installation

```bash
# install requirements
pip install -r requirements.txt
```

## Usage 

All of the model development process (preprocessing, training, and evalation) can be done by running each notebook.