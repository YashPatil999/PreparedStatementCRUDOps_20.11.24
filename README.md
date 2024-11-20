Person Management System
This project demonstrates a basic Java application for managing person details using JDBC and MySQL. The system allows CRUD (Create, Read, Update, Delete) operations on a database table personDetails.

Features:
Insert Data: Add a new person's details (ID, Name, Address) to the database.
Update Data: Modify existing person's details using their unique ID.
Delete Data: Remove a person's record from the database using their ID.
Show Data: Retrieve and display all records from the personDetails table.

Files:
PersonManagement.java
Contains the main method that provides a menu-driven interface for interacting with the system.
Allows the user to choose between Insert, Update, Delete, or Show operations using a switch-case structure.
Student.java
Implements database operations using JDBC.
Includes methods:
Insert(int pId, String pName, String pAddress) - Adds a record to the database.
Update(int pId, String pName, String pAddress) - Updates a record's details.
Delete(int pId) - Deletes a record based on the provided ID.
GetAllData() - Retrieves and prints all records.
Compile and run the PersonManagement.java file to start the application.
