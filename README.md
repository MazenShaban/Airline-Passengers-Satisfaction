# ✈️ Airline Passengers Satisfaction Analysis using Bayesian Methods

## Overview

This project explores passenger satisfaction in the airline industry using statistical and machine learning techniques, with a particular focus on **Bayesian methods**. We analyze customer reviews and service features to classify passengers as **satisfied** or **not satisfied**, leveraging **Gaussian Naive Bayes**, **Bayesian Inference**, and prior distribution concepts.

## Objectives

- Perform **exploratory data analysis** to understand key factors influencing satisfaction.
- Apply **Gaussian Naive Bayes** classifier.
- Use **Bayesian prior** (Beta) to model uncertainty in prediction and inference.
- Evaluate model performance using accuracy, precision, recall, and ROC-AUC.

## Concepts Covered

- Naive Bayes Classification
- Gaussian Naive Bayes
- Beta distribution as prior for binomial outcomes (e.g., satisfaction rate)

## Dataset

- **Source:** [Kaggle - Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- **Description:** This dataset contains survey responses from airline passengers including demographic information, in-flight service ratings, and satisfaction labels.

## Key Features in Dataset

- `Gender`, `Age`, `Flight Distance`
- Service ratings: `Seat comfort`, `Inflight wifi service`, `Cleanliness`, `Food and drink`
- `Departure Delay in Minutes`, `Arrival Delay in Minutes`
- `Satisfaction` (target variable)

## Notebook Highlights

- Data cleaning and preprocessing
- Visualization of satisfaction trends
- Bayesian modeling using Beta prior
- Posterior estimation and uncertainty quantification
