Getting and Cleaning Data Project
=================================
Goal                     
----

The purpose of this project is to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.


Input                              
-----

Data set: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 


Analysis Script                          
---------------

**run_analysis.R:** this script downloads the dataset, processes and tidies it for analysis then creates a tidy summary dataset for the final result.


1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Please see the `run_analysis.R` script for a detailed description of the implementation of each step used to accomplish the goals. 

Output
------

**Tidy dataset:** `TidyData.txt`
This is a  final tidy dataset. Presents the mean of each measurement variable for each subject and activity combination.            


Code Book
---------

**CodeBook.md:** describes the variables, the data, and any transformations or work that you performed to clean up the data
