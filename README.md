#Getting and Cleaning Data Course Project

This repo contains the R script and codebook for the Course Project for "Getting and Cleaning Data", a Coursera course offered by JHU.

The raw data for the project is  collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

The data for the project can be found at: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

#Script

The script performs the following:

**Part I:** downloads data collected from the accelerometers from the Samsung Galaxy S smartphone;

To comply with project requirements, I have placed this section in comments so the analysis file can be run starting from Part II, assuming the the working directory in R has been set to the folder where the downloaded data is unziped (the original data folder is named UCI HAR Dataset). 

**Please change your working directory in R accordingly before you try to run the script on your machine.**
If you have the original raw Samsung data available in the current working directory, just run:
source('./run_analysis.R')

**Part II:** Cleans the data:

1.  Merge the training and the test sets to create one data set.
2.  Appropriately labels the data set with descriptive variable names. (note: I label the columns before the extraction of the mean and std for simplicity)
3.  Extract only the measurements on the mean and standard deviation for each measurement. 
4.  Use descriptive activity names to name the activities in the data set
5.  From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.



#Datasets
##Raw dataset
For details on the original raw data, please refer to the README.txt and features_info.txt files that come with the data.

