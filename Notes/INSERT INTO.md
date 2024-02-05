Used to add new data to [[Databases]]
- Adds a new record to a [[Table]]
- Can contain values for some or all columns
- Can be combined with a [[SELECT]] statement -> [[INSERT INTO SELECT]]
>[!example]
>```SQL
>INSERT INTO spelling_team, (first_name, spelling) VALUES ('James', 10);
## Multiple Values
- You can insert multiple rows with a single INSERT statement:
>[!example]
>INSERT INTO spelling_team (first_name, spellings) VALUES ('James', 10), (Abigail', 9);

>[!warning]
>Puts [[NULL]] if column is not specified

