# 1.Projects

## Fandango Project

## Overview
if you are planning on going out to see a movie,how well ca you trust online reviews and ratings?Especially if the same company showing rating also makes money by selling movie ticktes. Do they have a bias towards rating movies higher than they should be rated

## Goal:
Your goal is to complete the task below based off the 538 article and see if you reach a similar conclusion.you will need to use your pandas and visualisation skills to determine if Fandango's ratings in 2015 had a bias rating movies better to sell more tickets

## Part One : Understanding the Background and Data
Task: Read this artcile : Be Suspicious Of Online Movie Ratings, Especially Fandango’s

Task: After Reading the article , read these two tables giving an overview of the two .csv files we will be working with:

The Data

This is the data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s.There are two csv files one with Fandango Stars and Displayed Ratings , and the other with aggregate data for movie ratings from other sites , Metacritic , IMDB and Rotten Tomatoes.

all_sites_score.csv and fandango_scrape.csv

## Part Two: Exploring Fandango Displayed Scores versus True USer Ratings
Let's first explore the Fandango rating to see if our analysis agrees with the article's conclusion.

## Fandango Scores vs All Sites
Finally let's begin to explore whether or not Fandango artificially displays higher ratings than warranted to boost ticket sales.

Combining the Fandango Table with the ALL suts table. Not every movie in the fandango table is in the All sites table,Since some fandango movies have very little or no reviews.we only want to compare movies that are in both DataFrames, So doing an inner merge to merge togethher both DataFrames on the FILM columns.

## Final
Visualizing the distribution of ratings across all sites for the top 10 worst movies.
