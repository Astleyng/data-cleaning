# data-cleaning

#Data cleaning Project

create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement. 

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names. 

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#Working Steps

1. Download the data source and save into a folder in your local drive. Folder Name: "UCI HAR Dataset".
2. Save "run_analysis.R" in the parent folder of "UCI HAR Dataset", then set it as your working directory using "setwd()" function in RStudio.
3. Run "source("run_analysis.R")", a new file will be generated "tidy_data.txt" in your working directory.

