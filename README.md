# MSSQLconnection

This is a repository to create a Java program that establishes a DB connection to MSSQL server locally.

Eventually I will create features that will pull data and insert data into the DB once I have time to create the Java layouts.


Essentially you need to setup:
MS SQL SERVER
Download SQL JDBC jar file
create or have a login on SQL Server
in your java class file, specify the class you will use from the .jar file.  in this case its "com.microsoft.sqlserver.jdbc.SQLServerDriver"
in your java class file, specify the server, username and password
