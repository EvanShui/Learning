# Creating Tables 
[__link for creating
tables:__][https://dev.mysql.com/doc/mysql-tutorial-excerpt/5.7/en/creating-tables.html]
* Prior to creating the table, you have to figure out how to structure the table and understanding what each table column's variable type is. 
## Altering Tables
* If make mistake, MySQL provides ALTER TABLE
## Columns 
[__link for column
types:__][https://dev.mysql.com/doc/refman/5.7/en/show-columns.html]
## Keys 
* (Empty key) 
  * Column either is either not indexed or is indexed as secondary column.
* PRI (Primary Key) 
  * Primary key is the primary identification of a given row in your table. 
  * Each row's primary key will uniquely identify that row.
* MUL (Multiple Key) 
  * Allows for multiple occurances of a given value. 
* UNI (Unique Key)
  * Key that enforces uniquenss on that set of columns
  * That column can only have unique values, if user tries to enter a row with a value that matches with an existing row, will throw error.
* 
