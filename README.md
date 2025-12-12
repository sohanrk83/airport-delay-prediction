# airport-delay-prediction
Final project for I310D: Human-Centered Data Science: predicting high-delay months at major U.S. airports

Group Members: Neera, Maanya, Sohan

Instructor: Professor Abhijit Mishra

Course: Human-Centered Data Science (Fall 2025)

# Project Overview

This project predicts high-delay months at major U.S. airports (ATL, DEN, DFW, LAX, ORD) using Logistic Regression and a simple MLP. We evaluate accuracy, fairness across airports, seasonal patterns, and model interpretability using LIME.

## Repository Structure

data/       - raw + cleaned datasets  
notebooks/         - Colab notebook (main model + demo UI)    
README.md         - instructions and project overview  
requirements.txt      - dependencies

## How to Run

Clone repo:

git clone https://github.com/USERNAME/airport-delay-prediction


Install requirements:

pip install -r requirements.txt


Open the notebook:

notebooks/final_model.ipynb

## Methods Used

Feature engineering

Logistic Regression

MLP Classifier

LIME interpretability

Fairness evaluation by airport

ROC & AUC analysis

## Key Visuals

Delay ratio per airport

Seasonal delay trend

Stacked delay cause chart

ROC curves

Feature importance bar plot

LIME explanation
