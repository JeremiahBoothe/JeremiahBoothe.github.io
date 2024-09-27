//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[SongProcessor](index.md)

# SongProcessor

[jvm]\
class [SongProcessor](index.md)(bridge: [HttpDatabaseBridge](../../jdbchttpsql.model/-http-database-bridge/index.md), logger: Logger)

A class that processes song data by interacting with both an HTTP database bridge and a logger. This class fetches song data, updates target times, and logs the progress.

## Constructors

| | |
|---|---|
| [SongProcessor](-song-processor.md) | [jvm]<br>constructor(bridge: [HttpDatabaseBridge](../../jdbchttpsql.model/-http-database-bridge/index.md), logger: Logger) |

## Functions

| Name | Summary |
|---|---|
| [processSongData](process-song-data.md) | [jvm]<br>suspend fun [processSongData](process-song-data.md)(targetTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html), timeHandler: [TimeHandler](../-time-handler/index.md)): [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html) |
