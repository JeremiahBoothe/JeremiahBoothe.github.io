//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[SQLQueries](index.md)/[ensureTableExists](ensure-table-exists.md)

# ensureTableExists

[jvm]\
fun [ensureTableExists](ensure-table-exists.md)()

Ensures that the 'metadata' table exists in the database.

Checks if the 'metadata' table is present by querying the `information_schema.tables`. If the table does not exist, it invokes the `createTables` method to create the necessary tables. Logs actions and errors during the process.

This method is designed to be called before performing operations that depend on the existence of the 'metadata' table.

#### Throws

| | |
|---|---|
| [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) | If an error occurs during the database check or table creation. |
