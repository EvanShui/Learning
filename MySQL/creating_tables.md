# Creating Tables 
Prior to creating the table, you have to figure out how to structure the table
and understanding what each table column's variable type is. 
## Variable Types 
1. varchar 
* Variable-length strings. 
* Length value is between 0 and 65,535. 
* Once declared to a specific length, varchar entries will take up the amount of
  space they naturally take up plus 1 byte due to trailing spaces UP TO the
  size they were defined to take up.
2. char 
* Static-length strings.
* Length value is divided up in x byte intervals. 
* Entries are stored and their size is static. Even if the entry is a blank
  string, will still take up the size that the char is pre-defined. 
3. date
4. int
