# in-memory-sql-go

Creating an in-memory SQL database in Go

```
$ go run *.go
Welcome to gosql.
# CREATE TABLE users (id INT, name TEXT);
ok
# INSERT INTO users VALUES (1, 'Phil');
ok
# SELECT id, name FROM users;
| id | name |
====================
| 1 |  Phil |
ok
# INSERT INTO users VALUES (2, 'Kate');
ok
# SELECT name, id FROM users;
| name | id |
====================
| Phil |  1 |
| Kate |  2 |
ok
```

Reference: 

1) [Database basics: writing a SQL database from scratch in Go](https://notes.eatonphil.com/database-basics.html)
2) [Reddit-hackernews](https://www.reddit.com/r/hackernews/comments/g0cbku/writing_a_sql_database_from_scratch_in_go/)
