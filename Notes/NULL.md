- NULL is a legal value in any column. It is outside the domain of any [[SQL Data Types|Data Type]]
-  It normally represents an absence of information or inapplicable value  
-  Other uses (bad practice):  
	-  Nothing (Empty)  
	-  False  
	-  0  
- Example:  
	 ```SQL
	 CREATE TABLE states (name TEXT, admissionToUnion INTEGER);  
		INSERT INTO states ('Puerto Rico', NULL);  
	``` 

## Comparison
- Comparing any value (including NULL itself) with NULL yields [[UNKNOWN]].
- A tuple is in a query answer if and only if the [[WHERE]] clause is TRUE (not FALSE or [[UNKNOWN]]).