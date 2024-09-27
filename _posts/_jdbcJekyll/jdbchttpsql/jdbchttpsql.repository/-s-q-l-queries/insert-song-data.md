//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[SQLQueries](index.md)/[insertSongData](insert-song-data.md)

# insertSongData

[jvm]\
fun [insertSongData](insert-song-data.md)(songData: [SongData](../../jdbchttpsql.data/-song-data/index.md))

Inserts a new song record into the database.

This method takes a `SongData` object and inserts its details into the `SongTable` in the database. The operation is performed within a transaction to ensure data integrity. If the insertion is successful, a confirmation message is logged. Any SQL or general exceptions encountered during the process are caught and logged.

#### Parameters

jvm

| | |
|---|---|
| songData | The song data to be inserted into the database. |

#### Throws

| | |
|---|---|
| [IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html) | If the song ID is null. |
| [SQLException](https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html) | If an error occurs during the SQL execution. |
| [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) | If an unexpected error occurs. |
