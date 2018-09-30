Set up :
-----------------
--Using NetBeans IDE Version 8.2
--Using Java JDK SE 8
--Using MySQL 5.7
--Using mysql-connector-java-5.1.45

Setting up database :
----------------------------
--Login into the database 
--Sql files are in LMS\Project\SQL
--To run a sql file on mysql command line, do SOURCE Path\to\file\<filename.sql>
--Run command.sql
--Populate the tables by running the following sql in mysql in the same order as below :

  1. book_data.sql
  2. authors_data.sql
  3. book_authors_data.sql
  4. borrower_data.sql
  5. book_loans_data.sql
  6. fines_data.sql

Importing project in NetBeans  : 
--------------------------------
--Import project into Netbeans 8.2 using following steps.
--Open NetBeans IDE 8.2
--Go to Files->Import Project->From ZIP(Browse the zip file)->Add jar file (mysql-connector-java-5.1.45-bin) when asked for.
--Project LMS will be imported
--Expand LMS->Source packages->lms->DBConnector.java->open
--Add user name and password of DB used instead of the default ones given.
--Save DBConnetor.java
--Compile DBCOnnector.java
--Select LMS project -> right click-> clean and build

Run GUI for front end of project
----------------------------------
--Select Borrower.java
--Right click -> run

