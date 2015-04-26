This code book describes the variables, the data, and the transformations involved in this course project.

Data set and files:

The experiment from which the data was collected involves 30 human subjects between age groups 19 and 48.  Each activities were recorded for each subject: walking, walking_upstairs, walking_downstairs, sitting, standing, and laying. The data set contains test and train data.

The following files were present in the data set.

README.txt, features_info.txt, features.txt, activity_labels.txt, train/X_train.txt, train/y_train.txt, test/X_test.txt, test/y_test.txt

Variables:

The following variables were estimated from these experiments, and these are self explanatory.

mean, std, min, max, energy, entropy, angle, bands energy, correlation, sma, meanfreq, kurtosis etc.


Transformation:

The transformation involved the following steps

1. The training and test sets were merged
2. Only the mean and std deviation variables were extracted for each measurement
3. Utilized descriptive activity names to name the activities
4. Appropriately labeled the data sets
5. Created a tidy data set of averages of each variable for each activity and subject