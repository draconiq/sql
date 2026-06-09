##### DISTINCTS AND TOP



###### REMOVES THE DUPLICATES(REPEATED VALUES) FROM THE DATA

###### EACH VALUE APPEARS ONLY ONCE



###### SYNTAX -



###### SELECT DISTINCT COL

###### FROM TABLE\_NAME



###### EX:

###### 

###### SELECT DISTINCT COUNTRY

###### FROM TABLE



###### DONT USE OT UNLESS ITS NECESSARY; IT CAN SLOW DOWN THE QUERY.



#### TOP

###### 

###### RESTRICT THE NUMBER OF ROWS RETURNED



###### SYNTAX -

###### 

###### SELECT TOP 3 \*

###### FROM TABLE

###### 

###### ONLY TOP 3 DATA WILL BE SHOWN IN OUTPUT, REST WILL BE EXCLUDED



###### RETREIVE TOP 3 CUSTOMERS WITH HIGHEST SCORE:



###### SELECT TOP 3 \* 

###### FROM CUSTOMERS

###### ORDER BY SCORE DESC



###### FOR LOWEST 2 

###### 

###### SELECT  TOP 2 \* 

###### FROM CUSTOMERS

###### ORDER  BY SCORE ASC

###### 

###### FOR RECENT 2 ORDERS 

###### 

###### SELECT TOP 2 \* FROM ORDERS 

###### ORDER BY ORDER\_DATE DESC 





