# getting-and-cleaning-data
The code was written based on the instruction of this assignment

Read training and test dataset into R environment. Read variable names into R envrionment. Read subject index into R environment.

    Merges the training and the test sets to create one data set. Use command rbind to combine training and test set
    Extracts only the measurements on the mean and standard deviation for each measurement. Use grep command to get column indexes for variable name contains "mean()" or "std()"
    Uses descriptive activity names to name the activities in the data set Convert activity labels to characters and add a new column as factor
    Appropriately labels the data set with descriptive variable names. Give the selected descriptive names to variable columns
    From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Use pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package
