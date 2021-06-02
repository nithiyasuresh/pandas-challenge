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

The next topic was to do gender demographics where i had to calculate the count and percentage of each gender and non-disclosed sectors while also categorising it based on players.
First step here was to group the SN column based on the gender, and give us a number using nunique.
Then calculate the percentage of gender, and rounding off to 2 decimal places on the percentage results.
Now to create a dataframe with the count and percentage, while sorting the table on total count, in descending order.
Last step was to add the "%" symbol to the percentage column, and display the created demographics table to match with the expected output.

The next topic was purchasing analysis based on gender.
This followed the same steps like the purchasing analysis done for player counts, where we did a groupby based on gender, and then calculated the average, purchase count, total purchase price and average total for the gender.
Then created a Dataframe with all the above calculated values, and rounded off the relevant columns to 2 decimal places, while also adding the "$" to the relevant columns.
Finally to display the created dataframe and match it with the expected output.

Similar calculations as above, followed for age demographics and the purchasing analysis based on the age demographics.

For top spenders, the calculations and creating dataframes were the same as above, while the final dataframe was also sorted in descending order based on the total purchase value.

Most popular items and most profitable items followed the same trend of calculations as above - the most popular items is sorted based on the purchase count, while the most profitable items was sorted based on the total purchase value.
