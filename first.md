**1. Exploratory analysis**
~~~ SQL
/*1.1 Data type of columns in a table*/
/*Sellers*/

SELECT * FROM Target.INFORMATION_SCHEMA.COLUMNS
where table_name = "Sellers";

~~~
