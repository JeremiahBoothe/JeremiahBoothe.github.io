//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[MongoDBRequests](index.md)/[insertSongData](insert-song-data.md)

# insertSongData

[jvm]\
fun [insertSongData](insert-song-data.md)(songData: [SongData](../../jdbchttpsql.data/-song-data/index.md))

Inserts the given song data into the MongoDB collection.

#### Parameters

jvm

| | |
|---|---|
| songData | The song data to insert. |

#### Throws

| | |
|---|---|
| [IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html) | if the song data ID is null.<br>Logs an info message when the song data is successfully inserted. Logs an error message if an error occurs while inserting the data. |
