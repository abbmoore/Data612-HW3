# Data612-HW3

#Here I have the yahoo stock dataset from the DATA612 page. There were issues adding the csv to the notebook so I deleted everything but the dates since that was the purpose of this assignment. This file is yahoo.csv.

#Additionally I have attached the homework3 notebook used to complete the assignment. 

#Finally, I have the yahoo_clean.csv file which is the finished csv exported.

#I began the assignment by importing pandas and numpty, followed with loading the csv file into the notebook.
#After I converted the dates in the dataset using pd.to_datetime to make the dates usable for calculation.
#Using the .max() function I found the most recent date in the dataset. and created a new calculated column that calculated the difference in days between the given date in the column and the most recent date. 

#I then created another column and converted the difference in days to months.

#Finally I exported the new dataset onto my computer.
