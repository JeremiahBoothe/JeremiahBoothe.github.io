//[jdbchttpsql](../../../index.md)/[jdbchttpsql.model](../index.md)/[HttpDatabaseBridge](index.md)/[processSongData](process-song-data.md)

# processSongData

[jvm]\
suspend fun [processSongData](process-song-data.md)()

Processes song data by fetching it from a remote API and inserting it into both SQL and MongoDB databases.

This function performs the following steps:

- 
   Ensures that the required MongoDB collection and SQL table exist.
- 
   Repeatedly fetches song data from a remote API.
- 
   If song data is retrieved, it is inserted into both SQL and MongoDB databases.
- 
   Logs the successful insertion of data and any errors that occur during the process.
- 
   Introduces a delay to throttle the requests.

#### Throws

| | |
|---|---|
| [Exception](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-exception/index.html) | if any errors occur during the processing of song data. |
