# tidytxt
 course project for Coursera "Getting and Cleaning Data"
@@ -1,18 +1,23 @@
# Getting-and-Cleaning-Data-Week-4-Assignment

This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.
* First, download and unzip the data file into your R working directory.
* Second, download the R source code into your R working directory.
* Finally, execute R source code to generate tidy data file.

## Data description
### Data description
The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data Y indicates activity type the subjects performed during recording.

## Code explaination
### Code explaination
The code combined training dataset and test dataset,  and extracted partial variables to create another dataset with the averages of each variable for each activity.

## New dataset
### New dataset
The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

## The code was written based on the instruction of this assignment
Read all the data and data names into R environment first.
### The code was written based on the instruction of this assignment
Read training and test dataset into R environment.
Read variable names into R envrionment.
Read subject index into R environment.

1. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set
