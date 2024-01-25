>[!example]
>```SQL
>SELECT title FROM Movies WHERE title LIKE ‘The%';

![[Pasted image 20240123105521.png]]

## Wildcard Characters '\%' and '\_'
- % is a wildcard that can match 0 or more characters
	- Probably should have been '\*', but already being used-
	- '\_' (underscore) is a wildcard representing a single character
		- Should have been '.' but again, already taken