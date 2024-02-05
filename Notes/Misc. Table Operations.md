`CREATE TABLE IF NOT EXISTS <table>;`
- Do not throw an error if you try to create a table that already exists
`DROP TABLE <table name>;` 
- Remove the entire table and all records of the table
`DROP TABLE IF EXISTS <table name>;`
- Same, but don’t throw an error if the table doesn’t exist