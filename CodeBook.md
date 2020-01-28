Code Book

Download the "UCI HAR Dataset" folder and read into R
Individually assign datasets to more readable names
     feautures
     activities
     subject_test
     x_test
     y_test
     subject_train
     x_train
     y_train
     
Merge all datasets into one using rbind and cbind

Extracted the average and std  from the merged dataset using the contains function
Used descriptive names from second column to replace the numbers in the first column

Cleaned up the old variable names by replacing the names

Lastly, finaldata is created which takes the average of each variable for each activity and each subject.
