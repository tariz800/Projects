# 1.Projects

## [Fandango Project](https://github.com/tariz800/Projects/blob/8b011eef8240881949fbdfe6dba8bb265fd61cef/Fandango/fandango-project.ipynb)

## Overview
if you are planning on going out to see a movie,how well ca you trust online reviews and ratings?Especially if the same company showing rating also makes money by selling movie ticktes. Do they have a bias towards rating movies higher than they should be rated

## Goal:
Your goal is to complete the task below based off the 538 article and see if you reach a similar conclusion.you will need to use your pandas and visualisation skills to determine if Fandango's ratings in 2015 had a bias rating movies better to sell more tickets

## Part One : Understanding the Background and Data
Task: Read this artcile : [Be Suspicious Of Online Movie Ratings, Especially Fandango’s](https://fivethirtyeight.com/features/fandango-movies-ratings/)

Task: After Reading the article , read these two tables giving an overview of the two .csv files we will be working with:

The Data

This is the data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s.There are two csv files one with Fandango Stars and Displayed Ratings , and the other with aggregate data for movie ratings from other sites , Metacritic , IMDB and Rotten Tomatoes.

[all_sites_score.csv](https://github.com/tariz800/Projects/blob/df375999301253db366fe3bf6b9bc4c7e689f338/Fandango/all_sites_scores.csv ) and [fandango_scrape.csv](https://github.com/tariz800/Projects/blob/df375999301253db366fe3bf6b9bc4c7e689f338/Fandango/fandango_scrape.csv)

## Part Two: Exploring Fandango Displayed Scores versus True User Ratings
Let's first explore the Fandango rating to see if our analysis agrees with the article's conclusion.
![](https://github.com/tariz800/Projects/blob/973fcc600ede94f67bcd2743f7a40ef695281d1f/images/true_user_vs_fandango.png)

## Fandango Scores vs All Sites
Finally let's begin to explore whether or not Fandango artificially displays higher ratings than warranted to boost ticket sales.
![](https://github.com/tariz800/Projects/blob/main/images/fandango_vs_all.png)
Combining the Fandango Table with the ALL suts table. Not every movie in the fandango table is in the All sites table,Since some fandango movies have very little or no reviews.we only want to compare movies that are in both DataFrames, So doing an inner merge to merge togethher both DataFrames on the FILM columns.

## Final
Visualizing the distribution of ratings across all sites for the top 10 worst movies.
![](https://github.com/tariz800/Projects/blob/main/images/final.png)

# 2.Project

## [Heart Attack Risk Predictor](https://github.com/tariz800/Projects/blob/main/Heart_Attack_Risk/heart_attack.ipynb)
In this project we will Make Machine learnings Algorithm that will help us predict the risk of a Heart Attack a person have.

We will do use various Algorithms to predict the result and see which one suits best. 

Data Analysis
Feature Engineering
Satandardization
Model Building
Predictions

![](https://github.com/tariz800/Projects/blob/main/images/heart_bar.png)

# 3.Project
## [Bike Rental Count Prediction uisng ML and Auto ML](https://github.com/tariz800/Projects/blob/main/Bike_Rental/bike-rental-prediction.ipynb)

![](https://github.com/tariz800/Projects/blob/a3a51ff178ab2620736cf0cd3b28d12b7ed97c41/images/download.jpeg)

# Backgroung:
## Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

## About the Dataset

### Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions,precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The core data set is related to  the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in [http://capitalbikeshare.com/system-data](http://capitalbikeshare.com/system-data). We aggregated the data on two hourly and daily basis and then extracted and added the corresponding weather and seasonal information. Weather information are extracted from [http://www.freemeteo.com](http://www.freemeteo.com).

### The objective of this Case is to Predication of bike rental count on daily based on the environmental and seasonal settings.

## Time Line of the Project:
- Importing Libraries and DataSet
- Data Analysis and Preprocessing
- Feature Engineering
- Model Building using ML
- Model Building and Prediction using H2O Auto ML


![](https://github.com/tariz800/Projects/blob/a3a51ff178ab2620736cf0cd3b28d12b7ed97c41/images/bike_pred.png)

# 4.Project

## [Heart Disease Using Logistic Regression](https://github.com/tariz800/Projects/blob/c8b93b90d731a3218bfba8c8d134df41d6efa921/HeartDisease/heartdiseaseprediction.ipynb)

## **GOAL: Creating a Classification Model that can predict whether or not a person has presence of heart disease based on physical features of that person (age,sex, cholesterol, etc...)**

# Data
This database contains 14 physical attributes based on physical testing of a patient. Blood samples are taken and the patient also conducts a brief exercise test. The "goal" field refers to the presence of heart disease in the patient. It is integer (0 for no presence, 1 for presence). In general, to confirm 100% if a patient has heart disease can be quite an invasive process, so if we can create a model that accurately predicts the likelihood of heart disease, we can help avoid expensive and invasive procedures.

Content

Attribute Information:

age
sex
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
target:0 for no presence of heart disease, 1 for presence of heart disease
Original Source: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

Creators:

Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

![](https://github.com/tariz800/Projects/blob/c8b93b90d731a3218bfba8c8d134df41d6efa921/images/heart_disease.png)
