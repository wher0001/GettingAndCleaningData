# GettingAndCleaningData

I have created a script in R named run_analysis.R
* There is data at the following location:
  * https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
* The data is from a study titled: _Human Activity Recognition Using Smartphones Data Set_
  * http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

 > For each record in the dataset it is provided: 
 > - Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
 > - Triaxial Angular velocity from the gyroscope. 
 > - A 561-feature vector with time and frequency domain variables. 
 > - Its activity label. 
 > - An identifier of the subject who carried out the experiment.
  
Inside the folder _/UCI HAR Dataset/_ from the above zip file above is a README.txt file that explains more about the contents.

**run_analysis.R** performs the following functions on the data found in the zip file and collected in the study 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

