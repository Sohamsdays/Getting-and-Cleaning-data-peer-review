## Getting and Cleaning Data codebook


## The original data was transformed by the doing the following steps  
## There are 5 steps which has to be done in serial order
1. Merge the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for measurement. 
3. Using descriptive activity names to name the activities in the data set.
4. Appropriate labeling the data set with descriptive names. 
5. Creating tidy data set with the average of each variable for each activity and each subject. 

## About R script
File with R code "run_analysis.R" perform the above 5 following steps.

## some information about the variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
