# Soil-Health-Management-System
Soil Health management system GUI
Explanation
Imports: Import necessary libraries including mysql.connector, tkinter, Faker, and others.
Database Connection: Connect to the MySQL database and create the soil_management database if it doesn't exist.
Table Creation: Create the soil_health table with necessary fields.
Data Generation: Define a function to generate random soil data using the Faker library.
Batch Insertion: Insert records in batches of 1,000 for efficiency.
GUI Interface: Create a Tkinter GUI for manual data entry and insertion.
Insert Record Function: Define a function to insert a single record into the database from the GUI.
Display Records Function: Define a function to display the most recent records in the GUI.
Run the GUI: Initialize and run the Tkinter main loop.
Close Connection: Safely close the database connection after the GUI is closed.
