This is the code for the course project, Getting and Cleaning Data.

The R script, run_analysis.R allows the user to do the following:


A. Download the dataset if it does not already exist in the working directory
B. Load the activity and feature info
C. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
D. Loads the activity and subject data for each dataset, and merges those columns with the dataset
E. Merges the two datasets
F. Converts the activity and subject columns into factors
G. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
H. The end result is shown in the file tidy.txt.