======================================================
Data- Overview:

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone

This repository contains the following

README.MD-->This file gives the overview of the dataset and how it was created
Codebook.md-->This file provides the information such as identifiers, Variables, labels and the summaries calculated.
run_analysis.R --> It's an R script. This script has been used to create a tidydataset. 
tidydataset.txt --> Tidydataset, which has the necessary information to investigate further

========================================================
Data Collection:

1. Downloaded the datafile from the source "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
2. Unzipped the datafile 
3. Loaded the Train and Test dataset programmatically and merged it on rowwise.
4. Merged the subjectID, activity name and activity code columnwise with the dataset as in step 3
5. Extract the columns corresponding to mean and Standarddeviation measurements from the dataset as in step 4
6. Modified the names of the columns as descriptive
7. Created the table with the extracted columns.
