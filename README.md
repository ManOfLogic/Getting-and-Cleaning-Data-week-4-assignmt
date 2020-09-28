This is the peer graded assigment for the Getting and Cleaning Data Coursera course. The code in run_analysis.R, does the following:

  1. Downloads the dataset(incase it does not exist in the working directory)
   
  2. Loads the activity and feature info along with both the training and test datasets, keeping only the columns which show a mean or standard deviation
   
   3.Loads the activity and subject data for each dataset, and merges those columns with the dataset
   
   4.Merges the two datasets
   
   5.Converts the activity and subject columns into factors
   
   6.Creates a tidy dataset that has the average value of each variable for every subject and activity pair.

The result is shown in the file tidy.txt
