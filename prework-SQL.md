# SQL Reading Notes

[Screenshot Land](/prework-SQL-screenshot-dump.md)

## Query Keywords

all caps not required, but is best practice. seems like column names are not case sensitive either.

- `SELECT` just like it sounds, selects columns by name. use commas to select multiple and wildcard to select all.
- `FROM` determines what table to query.
- `WHERE` used to declare a conditional statement; data filter.
- `AND/OR` chain together conditionals

Numerical Operators
![broken image](/img/num-conditionals.png)

Text Operators
![broken image](/img/text-conditionals.png)

- `DISTINCT` add just after SELECT. This will prevent the return of duplicate rows. Useful when you only need data from a single column or something?
- `ORDER BY column ASC/DESC` just like it sounds. Alpha/num sorts results. ASC/DESC are optional, ASC is default, but probably include anyways?
- `LIMIT x` determine max rows returned. What if LIMIT is higher than max rows in table?
- `OFFSET x` determine row count start. Can this only be used in conjunction with LIMIT? Seems like yes.
  - ex: webstore; shows 10 items per page so page 1 is `LIMIT 10 OFFSET 0` adn page 2 is `LIMIT 10 OFFSET 10`. Can sql do math or take refs? `OFFSET LIMIT*pageNumber` something like that?
- `JOIN tableB ON tableA.id = tableB.id` joins to tables according to the ON conditional. there are inner and outer joins, inner is implicit/default. If no ON conditional is set this will basically just multiply your tables together!!!

## Data Editing

### insert

- `INSERT INTO table` guess what this does. optional parens below to indicate which columns you want to fill, default is all
- `VALUES (...), (...)` declares values to add, these can be expressions. I think each paren represents a row and the items within are ordered by table column (schema?)

### update

safe updating practice: write it as a select query first, smart.

- `UPDATE table` im starting to see that the inital keywords are like HTTP verbs, or crud actions, which of course they are...
- `SET column = value` just like it sounds. this data must correspond to the table schema
- `WHERE conditional` if theres no conditional it would just make every value in a column the same thing

### delete

probs run this as a select first too...

- `DELETE FROM table` yeah, yeah
- `WHERE conditional` this is optional, but if left out all your table data will be delete

### create table

- `CREATE TABLE tablename` too many dinner guests? try this one simple trick!
- `IF NOT EXISTS` optional clause to prevent dupe table error. goes before table name
- `(columnname DataType TableContrstraint DEFAULT default_val, col...)` declare table schema after table creation, only column name and data type are required.

Data Types
![broken image](/img/data-types.png)

Common Constraints
![broken image](/img/constraints.png)

### alter table

- `ALTER TABLE tablename` ???
- `ADD colname ...` add new column w/ schema
- `DROP colname` delete a column
- `RENAME TO newtablename` rename your table

### delete table

- `DROP TABLE tablename` this one can take the if exsists clause as well, same format

[Screenshot Land](/prework-SQL-screenshot-dump.md)
