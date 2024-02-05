- [[Query]] within a [[Query]]
- Nested [[Query|Queries]] provide data to the enclosing [[Query]]
- Can return values OR lists of records
- Must be enclosed in parentheses '()'
>[!example]
>```SQL
>SELECT Artist.Name FROM Artist WHERE Artist.Name IN (SELECT Album.Title FROM Album);

- Subqueries often used to:
	- Perform tests for set membership
	- Make set comparisons
	- Determine set cardinality
>[!example]
>```SQL
>SELECT name FROM courses WHERE semester = 'Fall' AND name in (SELECT name FROM courses WHERE semester = 'Spring');

