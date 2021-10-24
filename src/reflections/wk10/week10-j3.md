# Welcome to SQL

## In a SQL table, what is the difference between information in a row and information in a column?

Information in a row is the information contained within an entire object, the column data is just similar data describing an attribute on multiple objects.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE IF NOT EXISTS characters(  
    id int NOT NULL primary key AUTO_INCREMENT comment 'primary key',
    name VARCHAR(20),
    age int,
    description VARCHAR(255)
) default charset utf8 comment '';

## What is the difference between the following statements:

DELETE FROM table_name;

-This statement brings joy. It will not delete your entire table, it will just delete an item from your table.

DROP TABLE table_name;

-This statement does not bring joy. This will ruin your life. This statement deletes the entire table, making you question if its really worth it to go on.

Project: https://github.com/ScottFennie/Knights