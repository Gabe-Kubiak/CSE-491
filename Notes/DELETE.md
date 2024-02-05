- Permanently removes record from a [[Table]]
- Can delete one or more records
- Use [[WHERE]] clause to delete specific records
>[!example]
>```SQL
>DELETE FROM spelling_team; -- removes all rows
 >DELETE FROM spelling_team WHERE got_answer_right = 'False'; --removes some rows

