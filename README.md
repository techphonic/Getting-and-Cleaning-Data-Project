# Getting-and-Cleaning-Data-Project

This repository hosts the R script as well as the supporting documentation for the "Getting and Cleaning data" course project. The R code for this project assumes you have downloaded and extracted the following zip file into your working directory.

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

run_analysis.R includes the R script
averages.txt is a tidy data set that reflects the output of run_analysis.R
Codebook.md will help you understand the results of averages.txt

##run_analysis.R
1. Merges the training and test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names.
5. Binds all the data in a single data set.
6. Creates a tidy data set with the average of each variable for each activity and each subject.
