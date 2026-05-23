# Space-Ship-Titanic-Competition
Dataset Overview

The dataset is based on a fictional space mission set in the year 2912. The Spaceship Titanic was carrying nearly 13,000 passengers on its journey to new habitable planets when it collided with a spacetime anomaly near Alpha Centauri. As a result, almost half of the passengers were transported to an alternate dimension.

The goal of this project is to predict which passengers were affected using the available records.

Files provided
train.csv
Contains around 8,700 passenger records along with the target column Transported. This is used to train the model.
test.csv
Contains around 4,300 passenger records without the target column. The model is used to predict whether these passengers were transported.
sample_submission.csv
Shows the required format for final submission.
🧾 Features in the dataset

Each passenger record includes:

PassengerId – Unique ID (group_id + passenger number)
HomePlanet – Planet the passenger came from
CryoSleep – Whether the passenger was in suspended animation
Cabin – Cabin information in format Deck/Num/Side
Destination – Destination planet
Age – Age of the passenger
VIP – Whether the passenger paid for VIP service
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck – Spending on different services
Name – Passenger name (not used in modeling)
Transported – Target variable (True/False)

Project Summary

In this project, I performed thorough exploratory data analysis (EDA), handled missing values, and applied feature engineering techniques to improve model performance.

Some of the engineered features include:

Total spending across services
Cabin split into Deck, Num, and Side
Group-based features like GroupSize and IsAlone
CryoSleep combined with zero spending indicator


Result
Kaggle Rank: 2079 / 2249
Score: ~0.74
This was my first Kaggle competition, and it helped me understand the full machine learning workflow in practice.
