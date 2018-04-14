# Variable Types 
## varchar 
* Variable-length strings. 
* Length value is between 0 and 65,535. 
* Once declared to a specific length, varchar entries will take up the amount of
  space they naturally take up plus 1 byte due to trailing spaces UP TO the
  size they were defined to take up.
## char 
* Static-length strings.
* Length value is divided up in x byte intervals. 
* Entries are stored and their size is static. Even if the entry is a blank
  string, will still take up the size that the char is pre-defined. 
## date / datetime / timestamp 
### DATE 
* Used for values with a date part but no time part. 
* Displays in 'YYYY-MM-DD' format.
### DATETIME
* Used for values that contain both date and time parts.
* Displays DATETIME values in 'YYYY-MM-DD HH:MM:SS' format.
* Size: 8 bytes
### TIMESTAMP
* Used for values that contain both date and time parts. 
* Displays TIMESTAMP values in '1970-01-01 00:00:01'.
* Size: 4 bytes
* lighter on database and are indexed faster.
## int
* Stores 4 bytes. 
* Max. value unsigned: very high. 
* Min. value unsigned: 0
* int(x) x<-- means you want the inter to be shown at most with x digits. So,
  store an integer that's larger than x digits, will only be displayed as if it
had x digits. Actual value will be stored though.
