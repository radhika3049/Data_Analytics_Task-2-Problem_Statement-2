# Data_Analytics_Task-2-Problem_Statement-2

As a data analysis intern, I need to analyze sports data for a client. I am given with two datasets

related to IPL (Indian Premier League) cricket matches. One dataset contains ball-by-ball data

and the other contains match-wise data. I need to import the datasets into an SQL database

and perform the tasks given in this assignment to find important insights from this dataset.

About the Data

The first CSV file is for ball-by-ball data and it has information of all the 193468 balls bowled

between the years 2008 and 2020. It has 17 columns and below is the details of those 17


Write queries for the following tasks:

1. Create a table named ‘matches’ with appropriate data types for columns

2. Create a table named ‘deliveries’ with appropriate data types for columns

3. Import data from CSV file ’IPL_matches.csv’ attached in resources to ‘matches’

4. Import data from CSV file ’IPL_Ball.csv’ attached in resources to ‘deliveries’

5. Select the top 20 rows of the deliveries table.

6. Select the top 20 rows of the matches table.

7. Fetch data of all the matches played on 2nd May 2013.

8. Fetch data of all the matches where the margin of victory is more than 100 runs.

9. Fetch data of all the matches where the final scores of both teams tied and order it in descending order of the date.

10. Get the count of cities that have hosted an IPL match.


Prerequesties before solving the tasks:

- Open the csv files and save as in 'CSV MS-DOS' format to avoid encryption (It is probably 'CSV comma delimited' prior).

- Remove all the commas contained in the observations using excel by, Selecting the column > Home > Editing tab > Find & Select > Replace.

- Change to yyyy-mm-dd format by right cick > Format cells > Number > Date > selecting 'yyyy-mm-dd' format > Ok. And save the file.

- For the sql version above 5.6, there must be a restriction to import file. So, you have to paste the importing file in the file directory. File directories are         mostly a hidden file.

  Check the directory below: You need to run the below command for extracting the path where you need to paste both the csv files.

  show variables like "secure_file_priv";
