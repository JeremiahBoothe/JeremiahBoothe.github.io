//[jdbchttpsql](../../../index.md)/[jdbchttpsql.model](../index.md)/[HttpDatabaseBridge](index.md)

# HttpDatabaseBridge

[jvm]\
class [HttpDatabaseBridge](index.md)(sqlQueries: [SQLQueries](../../jdbchttpsql.repository/-s-q-l-queries/index.md), mongoDBRequests: [MongoDBRequests](../../jdbchttpsql.repository/-mongo-d-b-requests/index.md))

A bridge connecting HTTP requests to database operations for fetching and storing song data. This class interacts with both SQL and MongoDB databases.

## Constructors

| | |
|---|---|
| [HttpDatabaseBridge](-http-database-bridge.md) | [jvm]<br>constructor(sqlQueries: [SQLQueries](../../jdbchttpsql.repository/-s-q-l-queries/index.md), mongoDBRequests: [MongoDBRequests](../../jdbchttpsql.repository/-mongo-d-b-requests/index.md)) |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>fun [close](close.md)() |
| [fetchSongData](fetch-song-data.md) | [jvm]<br>suspend fun [fetchSongData](fetch-song-data.md)(): [SongData](../../jdbchttpsql.data/-song-data/index.md)?<br>Fetches song data from a remote API endpoint. |
| [processSongData](process-song-data.md) | [jvm]<br>suspend fun [processSongData](process-song-data.md)()<br>Processes song data by fetching it from a remote API and inserting it into both SQL and MongoDB databases. |
