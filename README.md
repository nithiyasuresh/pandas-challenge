# pandas-challenge

Reading through the Heroes of Pymoli assignment, noted down in a notepad of the steps to be done.
Following the instructions, and created a new github repo for pandas assignment and named it pandas-challenge.
Cloned the repo to my laptop, so i can do regular commits from the folder into github.
Then created a folder for the assignment.  Did the pyschools by mistake first time around, and then deleted and created heroes of pymoli folder.
Copied across the Resources and the jupyter panda file into the github folder.
Did a commit to github, so the csv and panda file is stored into the github as a start.

When starting the assignment, first step was to import os, pandas, csv.
Assign a dataframe and define where the csv should be loaded from.
Read the csv file, and run the dataframe to load the file.

First step is to do a player count from the dataframe.
assign a name to find the total players. Using "unique" returned all the string in the column.
We needed the numbers to be returned, and so googling it, I found nunique, that returns the no of players rather than the name of players.
Created a dataframe, and give a column name "Total Players", and data to be picked up from "total_players" variable.
Finally displaying the dataframe, the display matched with the expected output.

Next step is to do Purchasing analysis.
In the main dataframe, i created a variable called unique_df to do the basic calculations  on Item ID, Price, Purchase ID columns, to calculate the count, mean and sum of the columns.
Then created a new dataframe called sumary with the calculated average, purchase_count, revenue and unique_df.
The output from the above didnt have any rounding off rule, and hence introduced the round function, to round off to 2 decimal places.
Finally to add the "$" sign before any money value in the new dataframe, for which i had to take BCS support to get the format statement right.
As a final step - displayed the output of the new dataframe - to verify that is the same as expected output.

