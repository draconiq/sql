#### DATA DEFINITION LANGUAGE: DDL



* ##### CREATE 
* ##### ALTER 
* ##### DROP



###### CREATE: 

###### &#x09;The CREATE statement is used to create new database objects 

###### &#x09;such as tables, databases, views, indexes, and procedures in a database.



###### SYNTAX-

###### 

###### &#x09;CREATE TABLE PERSONS(ID INT NOT NULL,

###### &#x20;       PERSON\_NAME VARCHAR(50) NOT NULL,BIRTH\_DATE DATE,

###### &#x20;       PHONE VARCHAR(15) NOT NULL,CONSTRAINT PK\_PERSONS PRIMARY KEY(ID));



###### ALTER:

###### &#x09;The ALTER statement is used to modify the structure of an existing database object, 

###### &#x09;such as adding, deleting, or modifying columns in a table.

###### 

###### SYNTAX- 

###### 

###### &#x09;ALTER TABLE TABLE\_NAME 

###### &#x09;ADD EMAIL VARCHAR(50)

###### 

###### DROP:

###### &#x09;The DROP statement is used to permanently remove an existing database object, 

###### &#x09;such as a table, database, view, or index.

###### &#x09;

###### 

###### &#x09;This permanently deletes the PERSONS table along with all its data. 

###### &#x09;⚠️ Once dropped, the table and its data cannot be recovered unless a backup exists

###### 

###### SYNTAX - 

###### 

###### &#x09;DROP TABLE TABLE\_NAME 

