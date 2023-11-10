# Run-Analysis-Getting-and-Cleaning-Data-Project
Data Science Using R Programming

Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist.
The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

GOAL - The goal is to prepare tidy data that can be used for later analysis. 

In run_analysis.R
1. Load dplyr package and imported and prepped the Data.
2. Load activity and features information to act as column headings for the data.
3. Load training datasets for X and Y groups.
4. Load test datasets for X and Y groups.
5. Load subject datasets for X and Y groups
6. created another dataset with only the mean and standard deviations data  -- this was done before merging the dataset.
7. Merged datasets to create a new tidy dataset.
8. created final dataset of the averages grouped by subject and activity code.

