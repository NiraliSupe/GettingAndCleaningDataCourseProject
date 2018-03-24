# Code Book

This code book summarizes the resulting data fields in `TidyData.txt`.

## The dataset includes the following files:

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the 
feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

The following files are available for the train and test data. Their 
descriptions are equivalent. 

- 'train/subject_train.txt': Each row identifies the subject who performed 
the activity for each window sample. Its range is from 1 to 30. 

- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal 
from the smartphone accelerometer X axis in standard gravity units 'g'. 
Every row shows a 128 element vector. The same description applies for the 
'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal 
obtained by subtracting the gravity from the total acceleration. 

- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector 
measured by the gyroscope for each window sample. The units are radians/second. 

## Identifiers

* `subject` - The ID of the test subject
* `activityName` - The type of activity performed when the corresponding measurements were taken

## Measurements

Variable                                         | Comments
-------------------------------------------------|----------------------------
timeBodyAccelerometer-MEAN()-X                   |  mean of tBodyAcc-mean()-X
timeBodyAccelerometer-MEAN()-Y                   |  mean of tBodyAcc-mean()-Y
timeBodyAccelerometer-MEAN()-Z                   |  mean of tBodyAcc-mean()-Z
imeBodyAccelerometer-SD()-X                      |  mean of tBodyAcc-std()-X
imeBodyAccelerometer-SD()-Y                      |  mean of tBodyAcc-std()-Y
imeBodyAccelerometer-SD()-Z                      |  mean of tBodyAcc-std()-Z
timeGravityAccelerometer-MEAN()-X                |  mean of tGravityAcc-mean()-X
timeGravityAccelerometer-MEAN()-Y                |  mean of tGravityAcc-mean()-Y
timeGravityAccelerometer-MEAN()-Z                |  mean of tGravityAcc-mean()-Z
timeGravityAccelerometer-SD()-X                  |  mean of tGravityAcc-std()-X
timeGravityAccelerometer-SD()-Y                  |  mean of tGravityAcc-std()-Y
timeGravityAccelerometer-SD()-Z                  |  mean of tGravityAcc-std()-Z
timeBodyAccelerometerJerk-MEAN()-X               |  mean of tBodyAccJerk-mean()-X
timeBodyAccelerometerJerk-MEAN()-Y               |  mean of tBodyAccJerk-mean()-Y
timeBodyAccelerometerJerk-MEAN()-Z               |  mean of tBodyAccJerk-mean()-Z
timeBodyAccelerometerJerk-SD()-X                 |  mean of tBodyAccJerk-std()-X
timeBodyAccelerometerJerk-SD()-Y                 |  mean of tBodyAccJerk-std()-Y
timeBodyAccelerometerJerk-SD()-Z                 |  mean of tBodyAccJerk-std()-Z
timeBodyGyroscope-MEAN()-X                       |  mean of tBodyGyro-mean()-X
timeBodyGyroscope-MEAN()-Y                       |  mean of tBodyGyro-mean()-Y
timeBodyGyroscope-MEAN()-Z                       |  mean of tBodyGyro-mean()-Z
timeBodyGyroscope-SD()-X                         |  mean of tBodyGyro-std()-X
timeBodyGyroscope-SD()-Y                         |  mean of tBodyGyro-std()-Y
timeBodyGyroscope-SD()-Z                         |  mean of tBodyGyro-std()-Z
timeBodyGyroscopeJerk-MEAN()-X                   |  mean of tBodyGyroJerk-mean()-X
timeBodyGyroscopeJerk-MEAN()-Y                   |  mean of tBodyGyroJerk-mean()-Y
timeBodyGyroscopeJerk-MEAN()-Z                   |  mean of tBodyGyroJerk-mean()-Z
timeBodyGyroscopeJerk-SD()-X                     |  mean of tBodyGyroJerk-std()-X
timeBodyGyroscopeJerk-SD()-Y                     |  mean of tBodyGyroJerk-std()-Y
timeBodyGyroscopeJerk-SD()-Z                     |  mean of tBodyGyroJerk-std()-Z
timeBodyAccelerometerMagnitude-MEAN()            |  mean of tBodyAccMag-mean()
imeBodyAccelerometerMagnitude-SD()               |  mean of tBodyAccMag-std()
timeGravityAccelerometerMagnitude-MEAN()         |  mean of tGravityAccMag-mean()
timeGravityAccelerometerMagnitude-SD()           |  mean of tGravityAccMag-std()
imeBodyAccelerometerJerkMagnitude-MEAN()         |  mean of tBodyAccJerkMag-mean()
timeBodyAccelerometerJerkMagnitude-SD()          |  mean of tBodyAccJerkMag-std()
timeBodyGyroscopeMagnitude-MEAN()                |  mean of tBodyGyroMag-mean()
timeBodyGyroscopeMagnitude-SD()                  |  mean of tBodyGyroMag-std()
timeBodyGyroscopeJerkMagnitude-MEAN()            |  mean of tBodyGyroJerkMag-mean()
timeBodyGyroscopeJerkMagnitude-SD()              |  mean of tBodyGyroJerkMag-std()
frequencyBodyAccelerometer-MEAN()-X              |  mean of fBodyAcc-mean()-X
frequencyBodyAccelerometer-MEAN()-Y              |  mean of fBodyAcc-mean()-Y
frequencyBodyAccelerometer-MEAN()-Z              |  mean of fBodyAcc-mean()-Z
requencyBodyAccelerometer-SD()-X                 |  mean of fBodyAcc-std()-X
requencyBodyAccelerometer-SD()-Y                 |  mean of fBodyAcc-std()-Y
requencyBodyAccelerometer-SD()-Z                 |  mean of fBodyAcc-std()-Z
frequencyBodyAccelerometerJerk-MEAN()-X          |  mean of fBodyAccJerk-mean()-X
frequencyBodyAccelerometerJerk-MEAN()-Y          |  mean of fBodyAccJerk-mean()-Y
frequencyBodyAccelerometerJerk-MEAN()-Z          |  mean of fBodyAccJerk-mean()-Z
frequencyBodyAccelerometerJerk-SD()-X            |  mean of fBodyAccJerk-std()-X
frequencyBodyAccelerometerJerk-SD()-Y            |  mean of fBodyAccJerk-std()-Y
frequencyBodyAccelerometerJerk-SD()-Z            |  mean of fBodyAccJerk-std()-Z
frequencyBodyGyroscope-MEAN()-X                  |  mean of fBodyGyro-mean()-X
frequencyBodyGyroscope-MEAN()-Y                  |  mean of fBodyGyro-mean()-Y
frequencyBodyGyroscope-MEAN()-Z                  |  mean of fBodyGyro-mean()-Z
frequencyBodyGyroscope-SD()-X                    |  mean of fBodyGyro-std()-X
frequencyBodyGyroscope-SD()-Y                    |  mean of fBodyGyro-std()-Y
frequencyBodyGyroscope-SD()-Z                    |  mean of fBodyGyro-std()-Z
frequencyBodyAccelerometerMagnitude-MEAN()       |  mean of fBodyAccMag-mean()
frequencyBodyAccelerometerMagnitude-SD()         |  mean of fBodyAccMag-std()
frequencyBodyAccelerometerJerkMagnitude-MEAN()   |  mean of fBodyBodyAccJerkMag-mean()
frequencyBodyAccelerometerJerkMagnitude-SD()     |  mean of fBodyBodyAccJerkMag-std()
frequencyBodyGyroscopeMagnitude-MEAN()           |  mean of fBodyBodyGyroMag-mean()
requencyBodyGyroscopeMagnitude-SD()              |  mean of fBodyBodyGyroMag-std()
frequencyBodyGyroscopeJerkMagnitude-MEAN()       |  mean of fBodyBodyGyroJerkMag-mean()
frequencyBodyGyroscopeJerkMagnitude-SD()         |  mean of fBodyBodyGyroJerkMag-std()

Transformations
---------------

1. Dataset was initially split into subject, activity, and features. Each of these were further split into test and train sets. Merging was performed to get everything in one dataset.

2. Dataset activity variable was merged with the activity lookup table to yield descriptive activity name.

3. Features were filtered to only those matching mean() or std(). Dataset was merged with derived feature code lookup table to get featureName.

4. Datset was melted with subject, activity, and feature as id variables.

5. An average was added per group of subject, activity, and feature

6. Since this is a TIDY data set, new descriptive columns were created to represent specific variables from the single feature variable (Domain,Instrument,Acceleration,StatVariable,Jerk,Magnitude and Axis) using grepl. The original feature is now redundant and removed.

7. The dataset is then written to `TidyData.txt` file
