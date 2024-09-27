//[jdbchttpsql](../../../index.md)/[jdbchttpsql.model](../index.md)/[HttpDatabaseBridge](index.md)/[fetchSongData](fetch-song-data.md)

# fetchSongData

[jvm]\
suspend fun [fetchSongData](fetch-song-data.md)(): [SongData](../../jdbchttpsql.data/-song-data/index.md)?

Fetches song data from a remote API endpoint.

This function attempts to retrieve song data by sending an HTTP GET request to the specified API endpoint. If the request is successful, the response body is parsed into a `SongData.SongData` object. In case of an exception, the function returns null and logs the error message.

#### Return

The fetched `SongData.SongData` object, or null if an error occurs.
