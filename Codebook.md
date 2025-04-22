# Codebook

This is a codebook for Coursera's course on Getting and Cleaning Data Module 4, that details the data and the codes used to perform this assignment.

## Data Source

Data was downloaded from [Human Activity Recognition Using Smartphones](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones).

## The R Script

1. The necessary packages were installed (in this case dplyr).
2. The data was downloaded as a zip file, and this was assigned a variable named filename.
3. The file was checked if it exists and then unzipped if it does.
4. The required datasets were imported and assigned their respective variables:
- features
- activities
- subject_test
- x_test
- y_test
- subject_train
- x_train
- y_train
5. The datasets were merged together by columns (for X and Y).
6. Only the measurements on the mean and standard deviation for each measurements were extracted.
7. Each dataset were renamed accordingly.
8. From this, the final data was obtained using the group_by() and summarise() functions.
9. And finally, as per the requirement of the assignment, the final data was saved as a text file in the working directory.
 





