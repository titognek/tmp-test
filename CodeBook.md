The raw data was downloaded from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
and processed according to description provided in the file README.md.
The original dataset included a total of 561 variable measures.

Processing of the datasets included:
- merging of the train and test datasets by including all the measured variables.
- addition of the subjects ID and the group assignment (test, train).
- addition of the activity description.
- selection of the columns with mean or standard deviation information for a total of 86
variable measures.
- column names for the selected variable measures are modified to improved readability
- The average for each of the 86 variables is calculated by grouping the data for each activity 
and subject.
- the resulting dataset is composed of 180 averaged observations for  30 subjects by 6 activity 
for 86 selected variables.
- detailed information of the data processing is available in the README.md file and in the annotation
of the script run_analysis.R

The average (mean) and standard deviation (stdDev) of these signals were used to estimate variables of the following feature vector:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

time_BodyAcc_XYZ
time_GravityAcc_XYZ
time_BodyAccJerk_XYZ
time_BodyGyro_XYZ
time_BodyGyroJerk_XYZ
time_BodyAccMagnitude
time_GravityAccMagnitude
time_BodyAccJerkMagnitude
time_BodyGyroMagnitude
time_BodyGyroJerkMagnitude
freq_BodyAcc_XYZ
freq_BodyAccJerk_XYZ
freq_BodyGyro_XYZ
freq_BodyAccMagnitude
freq_BodyAccJerkMagnitude
freq_BodyGyroMagnitude
freq_BodyGyroJerkMagnitude

The average (mean) of these signals were used to estimate variables of the following feature vector:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
freq_BodyAcc_Freq_XYZ
freq_BodyAccJerk_Freq_XYZ
freq_BodyGyro_Freq_XYZ
freq_BodyAccMagnitude_Freq
freq_BodyAccJerkMagnitude_Freq
freq_BodyGyroMagnitude_Freq
freq_BodyGyroJerkMagnitude_Freq
angle_tBodyAcc_Gravity
angle_tBodyAccJerk_Gravity
angle_tBodyGyro_Gravity
angle_tBodyGyroJerk_Gravity
angle_XYZ_Gravity

The set of variables that were estimated from these signals are: 
mean: Mean value
stdDev: Standard deviation

The complete list of variables of each feature vector is:

time_BodyAcc_mean_X_axis 
time_BodyAcc_mean_Y_axis
time_BodyAcc_mean_Z_axis
time_BodyAcc_stdDev_X_axis
time_BodyAcc_stdDev_Y_axis
time_BodyAcc_stdDev_Z_axis
time_GravityAcc_mean_X_axis
time_GravityAcc_mean_Y_axis
time_GravityAcc_mean_Z_axis
time_GravityAcc_stdDev_X_axis
time_GravityAcc_stdDev_Y_axis
time_GravityAcc_stdDev_Z_axis
time_BodyAccJerk_mean_X_axis
time_BodyAccJerk_mean_Y_axis
time_BodyAccJerk_mean_Z_axis
time_BodyAccJerk_stdDev_X_axis
time_BodyAccJerk_stdDev_Y_axis
time_BodyAccJerk_stdDev_Z_axis
time_BodyGyro_mean_X_axis
time_BodyGyro_mean_Y_axis
time_BodyGyro_mean_Z_axis
time_BodyGyro_stdDev_X_axis
time_BodyGyro_stdDev_Y_axis
time_BodyGyro_stdDev_Z_axis
time_BodyGyroJerk_mean_X_axis
time_BodyGyroJerk_mean_Y_axis
time_BodyGyroJerk_mean_Z_axis
time_BodyGyroJerk_stdDev_X_axis
time_BodyGyroJerk_stdDev_Y_axis
time_BodyGyroJerk_stdDev_Z_axis
time_BodyAccMagnitude_mean
time_BodyAccMagnitude_stdDev
time_GravityAccMagnitude_mean
time_GravityAccMagnitude_stdDev
time_BodyAccJerkMagnitude_mean
time_BodyAccJerkMagnitude_stdDev
time_BodyGyroMagnitude_mean
time_BodyGyroMagnitude_stdDev
time_BodyGyroJerkMagnitude_mean
time_BodyGyroJerkMagnitude_stdDev
freq_BodyAcc_mean_X_axis
freq_BodyAcc_mean_Y_axis
freq_BodyAcc_mean_Z_axis
freq_BodyAcc_stdDev_X_axis
freq_BodyAcc_stdDev_Y_axis
freq_BodyAcc_stdDev_Z_axis
freq_BodyAcc_meanFreq_X_axis
freq_BodyAcc_meanFreq_Y_axis
freq_BodyAcc_meanFreq_Z_axis
freq_BodyAccJerk_mean_X_axis
freq_BodyAccJerk_mean_Y_axis
freq_BodyAccJerk_mean_Z_axis
freq_BodyAccJerk_stdDev_X_axis
freq_BodyAccJerk_stdDev_Y_axis
freq_BodyAccJerk_stdDev_Z_axis
freq_BodyAccJerk_meanFreq_X_axis
freq_BodyAccJerk_meanFreq_Y_axis
freq_BodyAccJerk_meanFreq_Z_axis
freq_BodyGyro_mean_X_axis
freq_BodyGyro_mean_Y_axis
freq_BodyGyro_mean_Z_axis
freq_BodyGyro_stdDev_X_axis
freq_BodyGyro_stdDev_Y_axis
freq_BodyGyro_stdDev_Z_axis
freq_BodyGyro_meanFreq_X_axis
freq_BodyGyro_meanFreq_Y_axis
freq_BodyGyro_meanFreq_Z_axis
freq_BodyAccMagnitude_mean
freq_BodyAccMagnitude_stdDev
freq_BodyAccMagnitude_meanFreq
freq_BodyAccJerkMagnitude_mean
freq_BodyAccJerkMagnitude_stdDev
freq_BodyAccJerkMagnitude_meanFreq
freq_BodyGyroMagnitude_mean
freq_BodyGyroMagnitude_stdDev
freq_BodyGyroMagnitude_meanFreq
freq_BodyGyroJerkMagnitude_mean
freq_BodyGyroJerkMagnitude_stdDev
freq_BodyGyroJerkMagnitude_meanFreq
angle_tBodyAccMean_Gravity
angle_tBodyAccJerkMean_GravityMean
angle_tBodyGyroMean_GravityMean
angle_tBodyGyroJerkMean_GravityMean
angle_X_GravityMean
angle_Y_GravityMean
angle_Z_GravityMean


