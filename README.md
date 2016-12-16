# Getting-and-Cleaning-Data
## This is the final project for the getting and cleaning data course

This project provides a script called “run_analysis.R” which does the following:
1.	Create a place to download and unzip the “UCI HAR dataset” if it is currently not in the working directory

2.	A list of all files will be created

3.	Both the training and test datasets will be loaded, which are cleaned to include only columns with mean or standard deviation data

4.	Activity, subject and features data for each dataset are loaded and merged to the columns with the dataset

5.	All datasets are then merged to create the file “Data”

6.	Measurement names are tidied up

7.	Converts the “activity” and “subject” columns into factors

8.	Finally, a new dataset is created called “tidydata.txt” which consists the mean values of each variable for each subject and activity pair.

9.	All outputs will appear in the Global Environment pane of R Studio which can be selected and viewed
