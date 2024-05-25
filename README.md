# Airline Passenger Satisfaction Clustering

Welcome to the Airline Passenger Satisfaction Clustering project. This repository contains data and code for exploring and modeling customer satisfaction in the airline industry using K-Means clustering.

## Datasets

- **Raw Datasets**: The `airline_satisfaction_test.csv` and `airline_satisfaction_train.csv` files contain the original raw data used for initial exploration and cleaning.
- **Cleaned Dataset**: The `airplane_satisfaction_eda.csv` file is the cleaned version of the raw data, prepared and processed for analysis and modeling.
  
## Dataset Description

The Airline Customer Segmentation clustering model will utilize the Airline Passengers Satisfaction dataset from Kaggle: [Airline Passenger Satisfaction Dataset](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?select=test.csv)

| Variable                               | Description                                                               |
|----------------------------------------|---------------------------------------------------------------------------|
| Gender                                 | Gender of the passengers (Female, Male)                                   |
| Customer Type                          | The customer type (Loyal customer, disloyal customer)                     |
| Age                                    | The actual age of the passengers                                          |
| Type of Travel                         | Purpose of the flight of the passengers (Personal Travel, Business Travel)|
| Class                                  | Travel class in the plane of the passengers (Business, Eco, Eco Plus)     |
| Flight Distance                        | The flight distance of this journey                                       |
| Inflight Wifi Service                  | Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)    |
| Departure/Arrival Time Convenient      | Satisfaction level of Departure/Arrival time convenient                   |
| Ease of Online Booking                 | Satisfaction level of online booking                                      |
| Gate Location                          | Satisfaction level of Gate location                                       |
| Food and Drink                         | Satisfaction level of Food and drink                                      |
| Online Boarding                        | Satisfaction level of online boarding                                     |
| Seat Comfort                           | Satisfaction level of Seat comfort                                        |
| Inflight Entertainment                 | Satisfaction level of inflight entertainment                              |
| On-board Service                       | Satisfaction level of On-board service                                    |
| Leg Room Service                       | Satisfaction level of Leg room service                                    |
| Baggage Handling                       | Satisfaction level of baggage handling                                    |
| Check-in Service                       | Satisfaction level of Check-in service                                    |
| Inflight Service                       | Satisfaction level of inflight service                                    |
| Cleanliness                            | Satisfaction level of Cleanliness                                         |
| Departure Delay (Minutes)              | Minutes delayed when departure                                            |
| Arrival Delay (Minutes)                | Minutes delayed when Arrival                                              |
| Satisfaction                           | Airline satisfaction level (Satisfaction, neutral or dissatisfaction)     |

## Notebooks

- **Exploratory Data Analysis (EDA)**
  - **File**: `EDA-Airline.ipynb`
  - **Description**: This notebook contains a comprehensive exploratory data analysis of the airline satisfaction data. Key steps include data cleaning, handling missing values, visualizing data distributions, and identifying significant features influencing customer satisfaction.

- **Data Modeling**
  - **File**: `Data-Modeling-Airline.ipynb`
  - **Description**: This notebook focuses on the implementation of the K-Means clustering algorithm to segment passengers based on their satisfaction levels. It includes data preprocessing steps, model training, evaluation of the clustering results, and interpretation of the clusters.
