##Getting and Cleaning Data Project

This project is created to gather and clean activity data gathered from various subjects as part of "Getting and Cleaning data", available in coursera. More details of the data used in this project can be found at The UCI Machine Learning Repository

## Original dataset

The original dataset can be found on the UCI Machine Learning Repository site. The documentation of the original dataset, along with in-depth explanation of the experimental settings, can be found in the data directory

## Transformations

The transformations comprising the project are performed by the run_analysis.R. The script has inline comments marking out all each major step. In summary, the original dataset, which is split in a 70:30 ratio into training and test sets, is:

merged, both horizontally, across the train-test dimension, and vertically, along the subject-features-label dimension;

filtered, to retain only the columns for the mean and standard deviation values;

summarized, to show each of the variables averaged over each activity for each subject; and

cleaned up, so that variable names and factors are human readable

## Resulting dataset

The resulting dataset is saved in plain-text space-delimited file finalResult.txt in the data directory.

The dataset is tidy per the requirements of Week 1 of the course. It is in the wide-data format.

The data dictionary codebook.md contains descriptions of the variables in the new dataset.