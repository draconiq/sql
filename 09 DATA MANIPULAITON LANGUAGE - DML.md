#### DATA MANIPULAITON LANGUAGE - DML 

###### 

* ###### INSERT
* ###### UPDATE 
* ###### DELETE 

###### 

###### INSERT -

###### &#x20;         IF NO COLUMNS ARE SPECIFIED SQL EXPECTS VALUES OF

###### &#x09;ALL COLUMNS.

###### 

###### &#x09;The INSERT statement is used to add one or more new records (rows) into a table.

###### 

###### SYNTAX - 

###### 

###### INSERT INTO TABLE\_NAME(COL1,COL2.....)VALUES(VALUE1,VALUE2,....),(VALUE1,VALUE2,....)

###### 

###### THE NUMBER OF COLUMNS AND VALUES SHOULD MATCH EQUALLY 

###### EX: 2 COLUMNS SHOULD HAVE 2 VALUES 

###### &#x20;   4 COLUMNS SHOULD HAVE 4 VALUES

###### 

###### ORDER OF THE COLUMNS SHOULD MATCH THE VALUES WHILE INSERTING

###### 

###### FOR NOT DEFINING THE COLUMNS:

###### 

###### IF INSERTING VALUES WITHOUT MENTIONING THE COLUMN NAMES, YOU SHOULD SPECIFY THE

###### PROPER ORDER OF THE COLUMN IN CORRECT DIRECTION.



##### INSERT USING SELECT: 



###### Used to insert data from one table into another table.

###### 

###### SYNTAX - 

###### 

###### INSERT INTO TABLE\_NAME(COL1,COL2...)

###### SELECT COL1,COL2,....

###### FROM TABLE\_NAME   // TO COPY FROM SOURCE TABLE 

##### 

##### MODIFY/UPDATE:



###### The UPDATE statement is used to modify existing records in a table.

###### 

###### SYNTAX - 

###### UPDATE TABLE\_NAME

###### SET COL1=VALUE1,

###### &#x20;   COL2=VALUE2

###### WHERE <CONDITION> // ALWAYS USE WHERE TO AVOID UPDATING ALL ROWS UNINTENTIONALLY

###### 

###### TO CHECK IF ONLY THE UPDATING THE DATA USE THE SYNTAX:

###### 

###### SELECT \* FROM TABLE\_NAME

###### WHERE <CONDITION> // THIS SHOWS WHICH VALUES ARE GOING TO BE UPDATED WHEN EXECUTED



##### DELETE:



###### The DELETE statement is used to remove one or more existing rows from a table.

###### 

###### SYNTAX:

###### 

###### DELETE FROM TABLE\_NAME

###### WHERE <CONDITION> // ALWAYS USE WHERE CONDITION TO AVOID DELETING ALL ROWS

##### 

##### TRUNCATE: 

##### 

###### TRUNCATE is a DDL command used to remove all rows from a table quickly 

###### while keeping the table structure intact.

###### 

###### SYNTAX - 

###### 

###### TRUNCATE TABLE TABLE\_NAME

###### 

###### ALL THE DATA WILL BE DELETED FROM THE TABLE, BUT THE TABLE WILL VE STILL EXIST



&#x09;

