# Boston Housing Price Prediction

## Overview
The "Boston Housing Price Prediction" project is an end-to-end machine learning project that demonstrates the application of linear regression to predict housing prices based on various features. Utilizing the `load_boston` dataset from `sklearn`, this project encompasses a full data science workflow including initial Exploratory Data Analysis (EDA), data scaling, model training, and analysis of the trained model.

A simple front-end application built with Flask provides a user interface for interacting with the prediction model. The model and scaler are exported as pickle files for easy usage in applications.

## Features
- Comprehensive EDA of the Boston housing dataset.
- Data scaling and linear regression model training.
- Detailed analysis of model performance.
- Export of model and scaler for application use.
- Flask application for user interaction with the prediction model.
- Deployment on Heroku with full Docker and GitHub Actions integration for CI/CD.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Ling01234/Boston-Housing.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Flask app: `python app.py`


## Usage
After installation, you can interact with the Flask application to make predictions on housing prices based on input features.

## Deployment
This application is deployed on Heroku. The repository includes a `Dockerfile` and `main.yaml` for GitHub Actions.

## Contributions
Special thanks to [Krish Naik](https://www.youtube.com/user/krishnaik06) for his YouTube tutorials that contributed significantly to this project.
