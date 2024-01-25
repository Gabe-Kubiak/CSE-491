Used to designate columns that may not be NULL
>[!example]
>```SQL
>>CREATE TABLE students (msu_id TEXT UNIQUE NOT NULL, section INTEGER NOT NULL);

>[!warning]
>Raises error if a NULL value is inserted.

## Other Methods
- [[Primary Keys]]