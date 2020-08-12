# Getting-and-cleaning-data

This repository contains the code to obtain and clean the UCI Human Activity Recognition data set.

The R script, run_analysis.R, does the following:

- Download the dataset using the  url provided in the course project.
- Read the activity and feature data .
- Loads the training and testing datasets.
- Loads the activity and subject data for each dataset, and merges those columns with the
  dataset.
- Merges the two datasets.
- Eliminating all columns except those containg the mean and standard deviation.
- Creates a tidy dataset that consists of the average (mean) value of each variable for each  
  subject and activity pair.
- The final data  is shown in the file tidy.txt.

