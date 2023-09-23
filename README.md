# Bike_sharing_demand_prediction
# Table of Contents
Introduction

Problem Statement

Business Goal

Data Preparation

Model Building

Model Evaluation

Installation

# Introduction
This project aims to build a multiple linear regression model to predict the demand for shared bikes. The project is particularly relevant for BoomBikes, a US-based bike-sharing provider that has recently faced a decline in revenues due to the ongoing COVID-19 pandemic.

# Problem Statement
BoomBikes aspires to understand the demand for shared bikes among the people post-quarantine. The objective is to prepare a business plan to meet the demand levels and customer expectations once the economy restores to a healthy state.

# Business Goal
The model will help the management understand how exactly the demands vary with different features. This will enable them to manipulate their business strategy to meet the demand levels and customer expectations.

# Data Preparation
Convert variables like 'weathersit' and 'season' from numerical to categorical string values.

Consider keeping the 'yr' column as it might be a good predictor for the model.

# Model Building
The target variable for the model is 'cnt', which indicates the total number of bike rentals.

The dataset also contains 'casual' and 'registered' columns indicating the number of casual and registered users, respectively.

# Model Evaluation
The model's performance will be evaluated using the R-squared score on the test set.

# Usage
Clone this repository
git clone https://github.com/your-username/bike-sharing-demand-prediction.git

Go into the repository
cd bike-sharing-demand-prediction

Install dependencies
pip install -r requirements.txt


