# Getting-and-Cleaning-Data
##Getting and Cleaning Data Week 3 Assignment

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 

The goal is to prepare tidy data that can be used for later analysis.

One of the most exciting areas in all of data science right now is wearable computing - see for example this article:
http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/

Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

The data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The project requires to create a R script called run_analysis.R that does the following: 
- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set.
- Appropriately labels the data set with descriptive variable names. 
- Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

How does the run_analysis.R works :
- Load both test and train data
- Load the features and activity labels
- Extract the mean and standard deviation column names and data
- Process the data
- Merge and creates data set
- Output 2nd dataset

The result is saved as "./tidy_data2.txt".
It is a 180 rows (exclude header) x 68 columns.
The first column contains Subject IDs, the second column contains Activity names, follow by 
averages for each of the 66 attributes from column 3 to 68.

There are 30 subjects and 6 activities, thus 180 rows in this data set.
