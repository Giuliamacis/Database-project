# Database project 
by Francesco Capo, Martina Serandrei, Giulia Macis, Alessandro Ivashkevich

Inside the database-project folder you will find the original csv file, Airplane_Crashes_and_Fatalities_Since_1908.csv,
a file csv with the manipulated data, selection.csv, two file python one with the creation of the table, database.py,
and one with the queries, application.py.

1. Open file 'database.py'
2. Insert your mysql password
2. Run the file in order to create the table and put the data into them
3. Open the file 'application.py'
4. After you run it you will receive a choice between these inputs {1, 2, 3, 4, 5, 6, 7, 8, Quit}
5. Every time you insert one of the inputs above, you will enter the query chosen
6. Inside the query you are able to run it as many times as you want
7. To go back to the query selection you simply type 'home'
8. Finally, if you want to quit the application from the input list type 'Quit'.

Possible queries:

Query 1:

Allows the user to choose a country and checks if any airplane crashes have occurred there. It will display the relevant crash information if available.

Query 2:

Given a country, this query lists where crashes happened and provides the total number of fatalities. It also returns the accident with the highest number of deaths.

Query 3:

Asks the user to select a number between 0 and 520 (representing fatalities). If a crash with that number of fatalities exists, details are shown.

Query 4:

Finds airplanes that crashed more than once. It counts crashes per airplane and lists any that have been involved in more than one crash.

Query 5:

Lets the user select the reason for an airplane crash (e.g., "shot down," "engines failed," etc.) and fetches crashes based on the selected reason.

Query 6:

Allows the user to choose a year from 1980 to 2009. It shows aircraft crashes that occurred on the same route in the selected year.

Query 7:

Finds the operator with the most frequent crashes and calculates the total number of fatalities for that operator.

Query 8:

Visualizes the number of airplane crashes per year from the dataset. It generates a bar chart to show the trend of crashes over the years.
