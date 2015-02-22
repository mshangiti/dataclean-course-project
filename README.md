# About this Repo
This repo is used to submit a course project for "getting and cleaning data" course  (part of the Johns Hopkins data science track). The following files can be found in the repo:

* run_analysis.R
* tidy_data.txt

The idea is that the dataset provided (link can be found below), is not in the format needed for analysis. Thus, a script (run_analysis.R) is provided to read the dataset and turn it into a tidy dataset that can be used for analysis. The first file (run_analysis.R) is the script file; whereas, the second file (tidy_data.txt) is an example of the dataset that you will get if you run the script.

The following analysis is done when you run the provided script:
* In step1, the training and testing dataset are read and load to R.
* In step2, the training and testing dataset are merged togther into one dataset along with the subject and activity data.
* In step3, the column names are changed into a more friendly names (from V1,V2,etc to activity, subject, BodyAcc-mean()-X).
* in step4, we extract only the measurements on the mean and standard deviation for each measurement.
* in step5, we create an independent tidy dataset with the average of each variable for each activity and each subject, and returning back the result.

  #fulfilling requirement five
## Dataset source:
The dataset used with this project can be found at: [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

## Requirements to run the code
You will need R studio installed on your machine with the basic packages and the dplyr package as well.