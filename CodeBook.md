---
title: "CodeBook.md"
author: "Isaias Machado"
date: "2023-01-23"
output:
  html_document:
    df_print: paged
---

# Week 4 Assignment 

## Code book

id -> Person identification
      Identify the person who participated of the experiment as volunteer within an age bracket of 19-48 years. 
      
      0 .. 30 -> Valid values. 
      
Description -> Differs the activities (Type of movement) that describe the experiment.

               1. WALKING
               2. WALKING_UPSTAIRS 
               3. WALKING_DOWNSTAIRS, 
               4. SITTING, 
               5. STANDING, 
               6. LAYING  

timeBodyAcc-mean()-X -> Mean of time domain signal of body accelerometer at X axis.

                        Maximum value: 0.3 Hz

timeBodyAcc-mean()-Y -> Mean of time domain signal of body accelerometer at Y axis.

                        Maximum value: 0.3 Hz

timeBodyAcc-mean()-Z -> Mean of time domain signal of body accelerometer at Z axis.

                        Maximum value: 0.3 Hz

timeBodyAcc-std()-X ->  Standard deviation of time domain of body accelerometer at X axis.

                        Unit: Hz

timeBodyAcc-std()-Y -> Standard deviation of time domain of body accelerometer at Y axis.

                        Unit: Hz
                        
timeBodyAcc-std()-Z -> Standard deviation of time domain of body accelerometer at Z axis.
                        
                        Unit: Hz
                        
timeGravityAcc-mean()-X -> Mean of time domain of gravity accelerometer at X axis.

                        Unit: g

timeGravityAcc-mean()-Y -> Mean of time domain of gravity accelerometer at Y axis.

                        Unit: g
                        
timeGravityAcc-mean()-Z -> Mean of time domain of gravity accelerometer at Z axis.

                        Unit: g
                        
timeGravityAcc-std()-X -> Standard deviation of time domain of gravity accelerometer at X axis.
                        
                        Unit: g
                        
timeGravityAcc-std()-Y -> Standard deviation of time domain of gravity accelerometer at Y axis.
                        
                        Unit: g
                        
timeGravityAcc-std()-Z -> Standard deviation of time domain of gravity accelerometer at Z axis.
                        
                        Unit: g
                        
timeBodyAccJerk-mean()-X -> Mean of signal derived from body linear acceleration and angular velocity at X axis.

                        Unit: m/s³

timeBodyAccJerk-mean()-Y -> Mean of signal derived from body linear acceleration and angular velocity at Y axis.

                        Unit: m/s³
timeBodyAccJerk-mean()-Z -> Mean of signal derived from body linear acceleration and angular velocity at Z axis.

                        Unit: m/s³
                        
timeBodyAccJerk-std()-X -> Standard deviation signal derived from body linear acceleration and angular velocity at X axis.

                        Unit: m/s³
                        
timeBodyAccJerk-std()-Y -> Standard deviation signal derived from body linear acceleration and angular velocity at Y axis.

                        Unit: m/s³
                        
timeBodyAccJerk-std()-Z -> Standard deviation signal derived from body linear acceleration and angular velocity at Z axis.

                        Unit: m/s³
                        
timeBodyGyro-mean()-X -> Mean of time domain of body gyroscope at X axis.

                        Unit: -

timeBodyGyro-mean()-Y -> Mean of time domain of body gyroscope at Y axis.

                        Unit: -

timeBodyGyro-mean()-Z -> Mean of time domain of body gyroscope at Z axis.

                        Unit: -

timeBodyGyro-std()-X -> Standar deviation of time domain of body gyroscope at X axis.

                        Unit: -

timeBodyGyro-std()-Y -> Standar deviation of time domain of body gyroscope at Y axis.

                        Unit: -

timeBodyGyro-std()-Z -> Standar deviation of time domain of body gyroscope at Z axis.

                        Unit: -

timeBodyGyroJerk-mean()-X -> Mean of jerk signal derived from body gyroscope at X axis.

                        Unit: m/s³

timeBodyGyroJerk-mean()-Y -> Mean of jerk signal derived from body gyroscope at Y axis.

                        Unit: m/s³

timeBodyGyroJerk-mean()-Z -> Mean of jerk signal derived from body gyroscope at Z axis.

                        Unit: m/s³

timeBodyGyroJerk-std()-X -> Standard deviation of jerk signal derived from body gyroscope at X axis.

                        Unit: m/s³

timeBodyGyroJerk-std()-Y -> Standard deviation of jerk signal derived from body gyroscope at Y axis.

                        Unit: m/s³

timeBodyGyroJerk-std()-Z -> Standard deviation of jerk signal derived from body gyroscope at Z axis.

                        Unit: m/s³

timeBodyAccMag-mean() -> Body acceleration signal mean of the magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²
                        
timeBodyAccMag-std() -> Body acceleration signal Standard deviation of the magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeGravityAccMag-mean() -> Gravity acceleration signal Mean of the magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeGravityAccMag-std() -> Gravity acceleration signal standard deviation of the magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyAccJerkMag-mean() -> Body acceleration signal mean of the Jerk magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyAccJerkMag-std() -> Body acceleration signal standard deviation of the Jerk magnitude of accelerometer signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyGyroMag-mean() -> Body acceleration signal mean of the magnitude of gyroscope signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyGyroMag-std() -> Body acceleration signal mean of the magnitude of gyroscope signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyGyroJerkMag-mean() -> Body acceleration signal mean of the jerk magnitude of gyroscope signals were calculated using the Euclidean norm.

                        Unit: m/s²

timeBodyGyroJerkMag-std() -> Body acceleration signal standard deviation of the jerk magnitude of gyroscope signals were calculated using the Euclidean norm.

                        Unit: m/s²

frequenceBodyAcc-mean()-X -> Body's accelerometer frequency domain signal mean at X axis

frequenceBodyAcc-mean()-Y -> Body's accelerometer frequency domain signal mean at Y axis

frequenceBodyAcc-mean()-Z -> Body's accelerometer frequency domain signal mean at Z axis

frequenceBodyAcc-std()-X  -> Body's accelerometer frequency domain signal standard deviation at X axis

frequenceBodyAcc-std()-Y -> Body's accelerometer frequency domain signal standard deviation at Y axis

frequenceBodyAcc-std()-Z -> Body's accelerometer frequency domain signal standard deviation at Z axis

frequenceBodyAcc-meanFreq()-X -> Body's accelerometer frequency domain signal mean frequence at X axis

frequenceBodyAcc-meanFreq()-Y -> Body's accelerometer frequency domain signal mean frequence at Y axis

frequenceBodyAcc-meanFreq()-Z -> Body's accelerometer frequency domain signal mean frequence at Z axis

frequenceBodyAccJerk-mean()-X -> Body's accelerometer frequency domain signal jerk mean at X axis

frequenceBodyAccJerk-mean()-Y -> Body's accelerometer frequency domain signal jerk mean at Y axis

frequenceBodyAccJerk-mean()-Z -> Body's accelerometer frequency domain signal jerk mean at Z axis

frequenceBodyAccJerk-std()-X -> Body's accelerometer frequency domain signal jerk standard deviation at X axis

frequenceBodyAccJerk-std()-Y -> Body's accelerometer frequency domain signal jerk standard deviation at Y axis

frequenceBodyAccJerk-std()-Z -> Body's accelerometer frequency domain signal jerk standard deviation at Z axis

frequenceBodyAccJerk-meanFreq()-X -> Body's accelerometer frequency domain signal jerk mean frequence at X axis

frequenceBodyAccJerk-meanFreq()-Y-> Body's accelerometer frequency domain signal jerk mean frequence at Y axis

frequenceBodyAccJerk-meanFreq()-Z-> Body's accelerometer frequency domain signal jerk mean frequence at Z axis

frequenceBodyGyro-mean()-X -> Body's gyroscope frequency domain signal mean at X axis

frequenceBodyGyro-mean()-Y -> Body's gyroscope frequency domain signal mean at Y axis

frequenceBodyGyro-mean()-Z -> Body's gyroscope frequency domain signal mean at Z axis

frequenceBodyGyro-std()-X  -> Body's gyroscope frequency domain signal standard deviation at X axis

frequenceBodyGyro-std()-Y  -> Body's gyroscope frequency domain signal standard deviation at Y axis

frequenceBodyGyro-std()-Z  -> Body's gyroscope frequency domain signal standard deviation at Z axis 

frequenceBodyGyro-meanFreq()-X  -> Body's gyroscope frequency domain signal mean frequence at X axis

frequenceBodyGyro-meanFreq()-Y  -> Body's gyroscope frequency domain signal mean frequence at Y axis

frequenceBodyGyro-meanFreq()-Z  -> Body's gyroscope frequency domain signal mean frequence at Z axis

frequenceBodyAccMag-mean() -> Body's accelerometer magnitude frequency domain signal mean

frequenceBodyAccMag-std() -> Body's accelerometer magnitude frequency domain signal standard deviation

frequenceBodyAccMag-meanFreq() -> Body's accelerometer magnitude frequency domain signal mean frequence

frequenceBodyBodyAccJerkMag-mean() -> Body's accelerometer jerk magnitude frequency domain signal mean

frequenceBodyBodyAccJerkMag-std() -> Body's accelerometer jerk magnitude frequency domain signal standard deviation

frequenceBodyBodyAccJerkMag-meanFreq() -> Body's accelerometer jerk magnitude frequency domain signal mean frequence

frequenceBodyBodyGyroMag-mean() -> Body's gyroscope magnitude frequency domain signal mean

frequenceBodyBodyGyroMag-std() -> Body's gyroscope magnitude frequency domain signal standard deviation

frequenceBodyBodyGyroMag-meanFreq() -> Body's gyroscope magnitude frequency domain signal mean frequence

frequenceBodyBodyGyroJerkMag-mean() -> Body's gyroscope jerk magnitude frequency domain signal mean

frequenceBodyBodyGyroJerkMag-std() -> Body's gyroscope jerk magnitude frequency domain signal standard deviation

frequenceBodyBodyGyroJerkMag-meanFreq()" -> Body's gyroscope jerk magnitude frequency domain signal mean frequence


