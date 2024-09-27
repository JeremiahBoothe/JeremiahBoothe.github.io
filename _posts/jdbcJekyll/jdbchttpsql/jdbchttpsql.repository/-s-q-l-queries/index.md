//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[SQLQueries](index.md)

# SQLQueries

[jvm]\
class [SQLQueries](index.md)

A utility class to manage SQL queries for the 'metadata' table. Provides methods to create tables, ensure their existence, and insert song data.

## Types

| Name | Summary |
|---|---|
| [SongTable](-song-table/index.md) | [jvm]<br>object [SongTable](-song-table/index.md) : Table&lt;[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)&gt; <br>Represents the database table structure for storing song metadata. The table is named &quot;metadata&quot; and contains various columns for song data. |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>fun [close](close.md)() |
| [createTables](create-tables.md) | [jvm]<br>fun [createTables](create-tables.md)()<br>Creates necessary tables in the database if they do not already exist. Connects to the database, executes the SQL statement to create tables, and logs the operation status. Logs SQL and unexpected errors if any occur during the table creation process. |
| [ensureTableExists](ensure-table-exists.md) | [jvm]<br>fun [ensureTableExists](ensure-table-exists.md)()<br>Ensures that the 'metadata' table exists in the database. |
| [insertSongData](insert-song-data.md) | [jvm]<br>fun [insertSongData](insert-song-data.md)(songData: [SongData](../../jdbchttpsql.data/-song-data/index.md))<br>Inserts a new song record into the database. |
