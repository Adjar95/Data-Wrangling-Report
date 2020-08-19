# Data-Wrangling-Report
Wrangling and Analyzing Data

## Introduction


Real-world data rarely comes clean. Using Python and its libraries, we will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it.
This is called data wrangling. We will document the wrangling efforts in a Jupyter Notebook, then showcase them through analyses and visualizations using Python (and its libraries).
## Importing Libraries
To make use of the functions in a module, we import the needed libraries with an import statement.

## Gathering Data
Gathering data is the first step in data wrangling. Before gathering, we have no data, and after it, we do.

In this step we read the twitter-archive-enhanced.csv by using pandas read_csv function and image-predictions.tsv by using the same function with a little modification by adding sep = '\t'.

Seince there is it will takw time to request the API from Twitter and maybe reject the request, we read tweet's JSON data line by line and then transfering it into a pandas DataFrame by using the one provided one in Udacity class room.

## Assessing Data
Assessing the data is the second step in data wrangling.In this step we will inspecting the dataset for two things: data quality issues (i.e. content issues) and lack of tidiness (i.e. structural issues).

First, we will assess visually by looking in the data frame for some data quality and lack of tidiness observed in the data frames, then we assess programmatically by using libraries functions to find more data quality issues in the data frames.

## Cleaning Data
Cleaning the data is the third step in data wrangling. It is where we fix the quality and tidiness issues.

In this step we first make copies for all the dataframes to return a reference to the original DataFrames. Then for all the issues identified in the assess step, we dfine the issues and how we will fix it and then we transfer that into code and test it.

## Storing, Visualizing and Analyzing Data for this Project
Storing the clean DataFrame in a CSV file named twitter_archive_master.csv. Then preforming some visualiztion and analyation.
