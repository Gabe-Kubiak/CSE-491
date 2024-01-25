- [[SQL]] is primarily a query language




# Basic Querying
>[!info] Good practice to capitalize [[SQL]] [[Keywords]]
## Creating (Declaring) a Relation  
- Simplest Form 
```SQL
CREATE TABLE <name>
(  <list of elements>  
); 
```
## Elements of Table Declarations  
- Most basic element: an attribute and its type  
- The SQLite types are:  
	- INTEGER  
	- REAL  
	- TEXT  
	- BLOB (Binary Large Object)
## Example: Create Table  
```SQL
CREATE TABLE Movies (  
title TEXT,  
year INTEGER,  
length INTEGER,  
genre TEXT  
);  
```


