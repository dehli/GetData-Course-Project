GetData-Course-Project
======================

Course Project for Coursera's Getting and Cleaning Data.

Scripts:

run_analysis.R

	getFile()
		This function downloads the dataset and unzips it into the current working directory.
	
	mergeData()
		This function takes the dataset and merges the test and train data, as well as labeling.
		Note: The folder, UCI HAR Dataset must be in the current working directory.
	
	extractCols()
		This function extracts the columns that contain either mean or std.
		
	tidySet()
		This function returns a tidy dataset with the averages of each subject/activity combo.
		
	saveTidySet()
		This function saves a text file fo the tidy dataset in the current working directory.
