Basic Banking System
This project has been completed during my Capstone 2 Project.

Drop a star if this code helps you :)

Task assigned was as follows:
Create a simple dynamic website which has the following specs.

Start with creating a dummy data in database for upto 10 customers. Database options: Mysql, Mongo, Postgres, etc. Customers table will have basic fields such as name, email, current balance etc. Transfers table will record all transfers happened.
Flow: Home Page > View all Customers > Select and View one Customer > Transfer Money > Select customer to transfer to > View all Customers.
No Login Page. No User Creation. Only transfer of money between multiple users.
Host the website.
Techstack:
Client Side: Html, CSS, Javascript
Server Side: PHP
DBMS: MySQL

Project code description
index.php : First starting page of the project.
viewCustomers.php: This file is responsible for displaying customer table after fetching from database.
transfer.php: This is responsible for fund transfer where it displays the form asking for id of payer and payee and amount.
resultpage: This is the action page after user fills the form for transaction showcased by transfer.php. Here the actual transaction of money from database takes place. It is also responsible for error handling if any occurs in form filling. Also, it updates history table in DB which is keeping track of all transactions happened so far.
recordspage.php: This page shows the transaction record of all the money of customers taking place.
navbar.php: This is just responsible for showcasing the navigation bar at top of all pages.
spark_bank.sql: This is the database file made using MySQL DBMS. It consist of two tables accountdetails and history. Former is used to keep record of all customers and latter is going to keep track of all transaction taking place.