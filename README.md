CourseProject
=============
The data for the project can be downloaded at the link below: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

After download the file at the working directory, unzip it in the same folder.

The R script called run_analysis.R that does the following in order:
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

The result of the R script produces two files: merge_data.txt and data_with_means.txt. The first one is a data set with both the
data from training and test files. The second one is a tidy data set with mean of each variable for each activity and each subject.
