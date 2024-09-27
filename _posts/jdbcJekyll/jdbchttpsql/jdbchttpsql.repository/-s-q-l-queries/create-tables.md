//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[SQLQueries](index.md)/[createTables](create-tables.md)

# createTables

[jvm]\
fun [createTables](create-tables.md)()

Creates necessary tables in the database if they do not already exist. Connects to the database, executes the SQL statement to create tables, and logs the operation status. Logs SQL and unexpected errors if any occur during the table creation process.

#### Throws

| | |
|---|---|
| [SQLException](https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html) | If an error occurs while executing the SQL statement. |
| [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) | If an unexpected error occurs during the database operations. |
