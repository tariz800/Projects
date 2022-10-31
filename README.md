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
[](https://github.com/tariz800/Projects/blob/main/images/download.jpeg)

#Backgroung:
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

[](https://github.com/tariz800/Projects/blob/main/images/bike_pred.png)https://github.com/tariz800/Projects/blob/main/images/bike_pred.png
