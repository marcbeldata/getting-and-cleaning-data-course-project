# Getting and Cleaning Data Course Project
Marc Belzunces 26-12-2015

The run_analysis.R script performs the Course Project of the Getting and Cleaning Data Course of Coursera.

## How it works

0. Loading of useful libraries in R (reshape2).

1. Reads the general data.
2. Read the test and training data.
3. Merges the training and the test sets to create one data set.
4. Extract only the mean and standard devation for each measurement.
5. Change column names for appropriate labeling.
6. Creates a new tidy data set selecting only the mean for every measurement.
7. Export it to "tidy.txt", as required.

More detailed explanation for every step is in the comments of run_analysis.R code.
