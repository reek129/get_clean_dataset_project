# get_clean_dataset_project

Information about the data and R script used in this project

Dataset - Human Activity Recognition Using Smartphones Data Set 
Abstract: Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.

# Purpose
This script processes data from the Human Activity Recognition Using Smartphones Dataset to extract the average means and standard deviations of each variable for a given subject and activity, returning a tidy data frame containing these values.

The script was prepared to meet the requirements of an assignment in the Getting and Cleaning Data Course offered on Coursera

# Source Data
credit for the Human Activity Recognition Using Smartphones Dataset to:

Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto. Smartlab - Non Linear Complex Systems Laboratory DITEN - Universit? degli Studi di Genova. Via Opera Pia 11A, I-16145, Genoa, Italy. activityrecognition@smartlab.ws www.smartlab.ws

Data available here: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

With a full description here:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

# Assumptions

The script assumes the data will be found in the directory "./UCI HAR Dataset/" structured as it is in the linked archive. The script requires that the packages "plyr" and "reshape2" are available.

# USE
To use the script at the prompt, call source("~/run_analysis.R") correcting for file location, then run_analysis(). Assigning the ouput of the script to a data frame is recomended, since the resulting table is too large to simply read on screen.


