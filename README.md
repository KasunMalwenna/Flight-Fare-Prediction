# Flight Fare Prediction Project

## Overview
This repository contains the capstone project undertaken at [BrainStation](https://brainstation.io/) Data Science Bootcamp. The deployment phase as a web apllication be accessed at [Flight-Fare-Prediction-Web-App](https://github.com/KasunMalwenna/Flight-Fare-Prediction-Web-App.git) repository.

## Problem Statement
Fueled by inflation and due to limitations caused by the recent pandemic air ticket prices have skyrocketed over the last couple of years, rendering many airlines unprofitable and insolvent. This in turn has resulted in major travel disruptions while causing 2.3 million job depreciation.

Can Machine Learning and Deep learning techniques be employed to accurately predict the volatile air ticket prices such that airline companies can adjust their pricing strategies to increase revenue and remain competitive during this stagflation? 

## Introduction
Air ticket price has been erratic even before the pandemic as it is the most expensive and only worldwide rapid transportation method that connects people and business. It is influenced by numerous internal factors such, as travel date and time, fare class, and route and by external factors like holidays, and weather. To thrive and utilize optimum capacity, Airlines must attract passengers by offering the off best prices yet being competitive. Hence data-driven analytical methods are highly incorporated to automate the pricing mechanisms of airlines.

Developing robust algorithms have several potential applications within the aviation industry from determining ticket prices to personalized selling, crew management and fuel and route optimization. However, the scope of this project focuses on the portrayal of relationships from an abundance of historical data available to develop a predictive model which can forecast the ticket price within 10% of its true value. 

## use cases and challenges
There are two main use cases of flight price prediction in the travel industry. OTAs (Online travel agencies) and other travel platforms integrate this feature to attract more visitors looking for the best rates. Airlines employ the technology to forecast rates of competitors and adjust their pricing strategies accordingly.
A third use case, a passenger-side predictor suggests the best time to buy a ticket so that travelers can make informed decisions. Carriers, on their end, try to find out the optimal price they should set to maximize revenue while remaining competitive.

In both cases, the task is quite challenging because numerous internal and external factors influence airfares.

Internal factors include

- purchase and departure dates,
- the number of available airlines and flights,
- fare class,
- the current market demand
- flight distance
-
External factors embrace events going on in the arrival or departure cities — like

- holidays,
- concerts,
- sports competitions,
- festivals,
- Terrorist attacks,
- natural disasters,
- epidemic outbursts
-
Though it’s impossible to cover every external eventuality — say, nothing foreshadowed the 2020 coronavirus pandemic in the middle of 2019 — we still can predict quite a lot, using the right data and advanced machine learning (ML) models.

## Data
The data is secondary data publicly available at [Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction?select=Clean_Dataset.csv) and contains 300k instances of flight booking details for domestic travel between the busiest cities in India during the year 2022. Data was originally sourced using the “Octoparse” web scraping tool for 50 days on [Easemytrip](https://www.easemytrip.com/) which is a leading Indian-based travel platform, to obtain meaningful full insights by conducting various statistical hypothesis testing.

Although there is a cleaned version of the data, I have usined the unclened versions of the dataset and perfromed cleaning as required.

## Methodology
- The cleaning and preprocessing steps are detailed in [Data_Wrangling_and_EDA__Kasun_Malwenna.ipynb](Data_Wrangling_and_EDA__Kasun_Malwenna.ipynb) Notebook.
- Deep learning model development and evaluation is detailed in [Neural_Network_Flight_Fare_Kasun_Malwenna.ipynb](Neural_Network_Flight_Fare_Kasun_Malwenna.ipynb) Notebook
- ML learning model development, evaluation and final model selection is documented in [Modeling_Flight_Fare_Kasun_Malwenna.ipynb](Modeling_Flight_Fare_Kasun_Malwenna.ipynb) Notebook
