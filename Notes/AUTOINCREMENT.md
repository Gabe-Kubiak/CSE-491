- [[SQLite]] AUTOINCREMENT is a keyword used for auto incrementing a value of a field in the table. 
	- We can auto increment a field value by using AUTOINCREMENT keyword when creating a [[Table]] with specific column name to auto incrementing it.  
	- The keyword AUTOINCREMENT can be used with a [[INTEGER]] [[PRIMARY KEY]] field only
>[!example]
>```SQL
>CREATE TABLE table_name ( column1 INTEGER PRIMARY KEY AUTOINCREMENT, column2 datatype, column3 datatype, ..... columnN datatype);


# When to use?
- From https://www.sqlite.org/autoinc.html: "The AUTOINCREMENT keyword imposes extra CPU, memory, disk space, and disk I/O overhead and should be avoided if not strictly needed. It is usually not needed."
- If a column is INTEGER PRIMARY KEY, it already will autofill a unique value if a value isn't provided.
	- The only difference is AUTOINCREMENT guarantees monotonically increasing values, instead of just unique.
