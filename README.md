# Bike Rental Station Business Classification

## Overview

This project aims to classify the level of business at bike rental stations in New York City based on various factors. The model predicts how busy a station will be at a given time, helping optimize bike availability and station management.

## Dataset

The dataset consists of the following features:

- Temperature

- Rain

- Wind Speed

- Latitude&Longitude

- Time

- Day of Week

- Date

## Model

The classification model uses supervised learning techniques to predict the level of busyness at a station. The main model used is **ensemble voting of XGBoost (XGBClassifier) and Random Forest** due to its high efficiency and performance in handling structured data.

## Preprocessing Steps:

- **Data Cleaning** - Handling missing values, removing duplicates, and ensuring data integrity.

- **Feature Engineering** - Creating meaningful features such as rush hour indicators and weather effects.

- **Normalization & Standardization** - Ensuring numerical features are scaled appropriately.

- **Handling Class Imbalance** - Using techniques like oversampling or class weighting to address any imbalance in the dataset.

## Model Training & Evaluation

- **Algorithm:** ensemble voting of XGBoost (XGBClassifier) and Random Forest

- **Evaluation Metrics:** Weighted F1-score

- **Cross-Validation:** Applied to ensure model generalization

## Results

The model achieved a Weighted F1-score of **51%** on the test dataset.

## Challenges & Improvements

### Challenges:

- Feature selection played a crucial role in improving performance.

### Potential Improvements:

- Integrating real-time data for live predictions.



## Contributors

- Roy Shem Tov

- Eyal Grinfeld

## License

This project is licensed under the MIT License.

