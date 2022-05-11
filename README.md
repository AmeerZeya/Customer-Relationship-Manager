# Customer-Relationship-Manager
Web app to manage the customers name and email address developed using Java , Spring framework , HTML and CSS.

Users can do basic CRUD operation in the Web app .

# Local Installation
  1. Download the zip or clone the repository to a folder.
  2. Import the folder to Eclipse ( or your preferred IDE )
  3. create database and table via below mentioned sql script ( project DB dialect mySql )
  4. download and install Tomcat server 
  5. run the application on the server via the IDE


#Sql-script 

*CREATE DATABASE  IF NOT EXISTS `web_customer_tracker` 
USE `web_customer_tracker`;
 
*DROP TABLE IF EXISTS `customer`;*

*CREATE TABLE `customer` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(45) DEFAULT NULL,
  `last_name` varchar(45) DEFAULT NULL,
  `email` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`id`)
) 

INSERT INTO `customer` VALUES 
	(1,'Abhisheak','Roy','abhiroy@yahoo.com'),
	(2,'Aditya Mohan','Jha','jadityamohanjha@yahoo.in'),
	(3,'Ameer','Zeya','ameerzeya@yahoo.in'),
	(4,'Jatin','Nijawan','jatinNijhawan@gmail.com'),
	(5,'Shewtank','Mishra','shwetankmishra@gamil.com');*


# Usage
Click on soundCloud extension and use it to change/repeat/like/play/pause songs.
