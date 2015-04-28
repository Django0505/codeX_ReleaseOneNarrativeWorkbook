#Importing data into MySQL

There are various different ways to import data into a MYSQL database. You can either write a program using Node JS for example to read a CSV file and then execute ```insert``` statements to import the data into the database or you could use the ```LOAD FILE``` command from MySQL or you can you the import function from PhpMyAdmin.

Once the data is in your database you then need to write some insert statements to create the data in the correct tables. You will need to write some SQL joins to insert the correct foreign keys into the tables.

##Source data

To safe you some time here is a MySQL dump that already contains some data for Nelissa's Sales and Purchase history. You can use them as a baseline for your database. 

Here is the dump file:
