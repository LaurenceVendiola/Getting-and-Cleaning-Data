# Getting-and-Cleaning-Data
## Overview
This repository contains the code and documentation for the Coursera "Getting and Cleaning Data" course project. The goal of the project is to demonstrate your ability to collect, clean, and tidy a dataset so that it is ready for later analysis.

The dataset used in this project is from the UCI Human Activity Recognition Using Smartphones Data Set, which contains data collected from the accelerometers and gyroscopes of Samsung Galaxy S smartphones.

## Contents
run_analysis.R: The main R script that downloads the data, processes it, and outputs a tidy dataset.
Vendiola_tidyData.txt: The resulting tidy dataset containing the average of each variable for each activity and each subject.
README.md: This file explaining the project and how everything works.

##Summary of run_analysis.R
The script performs the following steps:
Setup: Loads required packages and downloads the data.
Read Metadata: Loads the features and activity labels.
Select Features: Filters for only mean and standard deviation measurements.
Read and Label Training/Test Sets: Reads, labels, and combines subject, activity, and measurement data.
Merge Datasets: Combines the training and test sets.
Apply Descriptive Labels: Converts numeric activity codes to descriptive names.
Reshape and Aggregate: Creates a tidy dataset with the average of each variable for each subject and activity.
Output: Writes the tidy data to Vendiola_tidyData.txt.
