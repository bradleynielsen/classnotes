# classnotes

MySQL

SHOW DATABASES;
-- ^^^ This shows all databases avalible

CREATE DATABASE bears;
-- ^^^ Creates a new database

USE bears;
-- ^^^ Selects the movies database to use

SELECT DATABASE();
-- ^^^ Shows what database we are working in

CREATE TABLE happyBears (id INT PRIMARY KEY AUTO_INCREMENT, name VARCHAR(30) NOT NULL, favFood VARCHAR(30) NOT NULL, personality VARCHAR(30));
-- ^^^ Creates a table in our database

SHOW TABLES;
-- ^^^ Shows all tables

DESCRIBE happyBears;
-- ^^^ Shows the specific table

INSERT INTO happyBears
  (name, favFood, personality)
VALUES
  ("Nom Nom", "Tacos", "Mean"),
  ("Rawr", "Fish Tacos", "Happy"),
  ("Blue", "Cake", "Happy"),
  ("Buddy", "Chicken", "Mean"),
  ("Jimm", "Candy", "Mellow");
-- ^^^ Inserting many lines of data into the table

SELECT * FROM happyBears;
-- ^^^ Shows all data in table

-- DROP DATABASE bears;
-- ^^^ If needed to delete BD or Test
