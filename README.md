# Pewlett-Hackard-Analysis
Pewlett Hackard analysis

# Used an ERD to understand relationships between SQL tables 

I have created the The Entity Relationship Diagram which includes all correct tables and each table has the correct column names, the correct corresponding data types, Primary Keys set for each table and tables are correctly related using Foreign Keys

# The report

The ask for my analysis was to determine the total number of employees per title who will be retiring, and identify employees who are eligible to participate in a mentorship program. This information will help Bobby’s manager prepare for the “silver tsunami” as many current employees reach retirement age.

To solve the problem I created 17 tables in the EmployeeDB database.I created the tables and copied the data from the CSVs provided.Then to find the retirement eligibility,I created new tables to hold info like retirement info.I joined the departement and dept_manager table by using INNER JOIN.Then  I selected the current employeesfrom retirement_info table and joining with dept_emp. I got the employee count by department number.  41380 employees were retiring and 2382 eligible for memtorship.

I tried a lot of other variations in this process for further analysis is by taking sales and dev dept. List of Sales employee and maybe combining two departements Sales and Developments.

# Used if/elif/else statements

Used if/elif/else statements to filter the city_data_df DataFrame based on the minimum and maximum temperature, and whether it is either raining and snowing or not to get the cities that meet the customer criteria.
The code will prompt the customer to get the following information The minimum temperature preference, The maximumtemperature
preference, If they want it to be raining or not, If they want it to be snowing or not.

# Created a New Dataframe with Hotel Information Using Google API Places and try/except block

I have written the code to search for a hotel using a Google API and the JSON data is retrieved. I have used the try/except block to add the hotel to the new DataFrame, and the IndexError is resolved.I have saved and uploaded the DataFrame to a CSV file.


# Created a pop-up marker with city and weather data and hotel name

I have created a marker layer map with a pop-up marker for each city that includes: Hotel name, City, Country, Current weather
description with the maximum temperature. I have saved and uploaded the new marker layer map as PNG

# Created a directions layer map to travel between citie

I have written the code to filter the vacation DataFrame for four cities to travel to.
I have written the code to get the latitude and longitude pairs for each city to visit.
I have created an itinerary map between the cities 
I have saved and uploaded the directions layer map as PNG.

# Created a pop-up marker for each city on the itinerary

I have craeted a new DataFrame that contains the cities in the itinerary.
I have craeted a marker layer map with a pop-up marker for the cities in the directions layer map which has the following information:
● Hotel name
● City
● Country
● Current weather description with the maximum temperature
I have saved and uploaded the new marker layer map for the four cities as PNG
