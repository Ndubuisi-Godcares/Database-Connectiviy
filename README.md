# Database-Connectiviy

This Java program creates several tables for a medical database using JDBC and MySQL.

Setup
To use this program, you need to have the following:

MySQL database installed on your system
JDK installed on your system
MySQL Connector/J driver added to your project

Usage
Create a new Java project in your favorite IDE (e.g. Eclipse, IntelliJ IDEA).
Copy and paste the contents of the Database_connection.java file into a new class in your project.
Add the MySQL Connector/J driver to your project's classpath.
Update the username, password, and url variables with your own database credentials.
Run the main method in the Database_connection class.
Check your database to ensure that the tables have been created successfully.

Notes
This program uses the CREATE TABLE SQL command to create the necessary tables for a medical database.
Each table has its own unique schema with specific column names and data types.
The program also includes foreign key constraints to ensure data integrity.
The IF NOT EXISTS clause is used to avoid errors when creating tables that may already exist in the database.
The SQLException is caught and handled to provide helpful error messages to the user.
