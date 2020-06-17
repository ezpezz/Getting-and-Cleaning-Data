# Getting and Cleaning Data - Coursera Project

## Author: 
Eiren Sweetman

## Goals of the project

1. A tidy data set that can be used for later analysis
2. A link to a Github repository with your script for performing the analysis
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. Also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
4. Analysis R Script

## Project summary

The data we are working is data collected from accelerometers from the Samsung Galaxy S smartphone. 
A description of the data from the original site can be found here:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

And the original data for the project here:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The R script, called run_analysis.R, does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
