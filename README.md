# ASSOCIATE MANAGEMENT SYSTEM -AMS

## Project Description
This is a project which is created in hive. 
The project was to create and maintain a database for candidate enrollment  where they provide training for various courses . 
We have created two tables in MySQL and import then to HDFS using SQOOP.
In this project we have created night tables from the two datasets. 
We have performed various operations in this project like table join , partitioning, updation etc. We have also performed queries in tables where we have extracted the data from it. 
We have run this project in hive terminal in GCP and CDH5.
- **Master.txt** *conatins all the information about the students.*
- **gcpProjectCommands.txt** *contains commands to create all the tables that are required for the project.*
- **queriesForHive.txt** *contains all the queries run on the project using hive.*
- **table4.txt** *conatins all the payment datails about the courses and how much student has paid, type of payments etc.*

## Technologies Used
* Hadoop
* Hive
* MySQL
* Sqoop
* Cloudera 5

## Features
1. Management team will be able to fetch number of students enrolled.

2. They can fetch the list of students who done the demo or missed the demo.

3. This project has features like update, delete and append a new set of rows.

4. Management team can perform bucketing and partitioning if required.

5. We can also perform CRUD operation on our payment table because of its ORC nature.

6. In this project all the tables overwritten from master table. So we do not need to update each table individually.

To-do list:
* Create a user interface so that it would be easier for user to register on the website.
* More courses are need to added.

## Getting Started
   
1. Create two table in MySQL Enquiry and Payments.
2. Insert data in these table using load method in SQL you can use gcpProjectsCommand.txt file for the reference and use master.txt file for enquiry table and table4.txt for payments table.
3. import these table from MySQL to HDFS using Sqoop.
4. Create required tables in Hive and these should be in ORC format so that you can delete, update and insert data easily.
5. Load all the data in hive tables that you have imported in HDFS from MySQL.
6. You can also do paritions and bucketing to make the hive faster to work on a specific data.


## Contributors

- Suleman Salmani
- Eswar Naidu
- Neha Ghosh
- Subodh Kumar


