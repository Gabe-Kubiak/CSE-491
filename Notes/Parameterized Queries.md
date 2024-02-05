>[!example]
>```python
>conn = sqlite3.connect(":memory:")
>conn.execute("CREATE TABLE students
>(name TEXT, age INTEGER);")
>conn.execute("INSERT INTO students VALUES ('James’, 30);")
>## What if we wanted to add a python integer? 
>Steve_age = 23 conn.execute( "INSERT INTO students VALUES ('Steve', " + str(steve_age) + ");" )

Used to pass python objects into queries without needing to manually convert to strings. 
>[!example]
>```python
>Steve_age = 23 conn.execute("INSERT INTO students VALUES ('Steve', ?);", (steve_age,)) row = ('Tim', 45)
> conn.execute("INSERT INTO students VALUES (?, ?);", row)

Used to stop [[SQL Injection]] Attacks (Why we use Parameterized Queries)
![[Pasted image 20240130111436.png]]
## Explanation
- The problem is if we wrote code like this:
>[!example]
>```python
>name = "Robert'); DROP TABLE students;
>--" conn.execute("INSERT INTO students VALUES ('" + name + "');") 
># INSERT INTO students VALUES ('Robert');
> # DROP TABLE students; --');

 >[!warning]
 >The input would be allowed to execute arbitrary queries against the database.
 
 