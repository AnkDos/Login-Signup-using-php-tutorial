# Login-Signup-using-php-tutorial By Ankur Pandey(AnkDos)

Creating a Login and Signup system using PHP tutorial.
We will be saving the data using MySQL

Creating Database and Tables :

//Copy Below this to

## create database your_database_name;
## use database your_database_name;
 CREATE TABLE `users` (
   id int(20) AUTO_INCREMENT Primary key ,
   username varchar(65) NOT NULL ,
   password varchar(65) NOT NULL ,
   email varchar(65) NOT NULL 
    );

// Above this


