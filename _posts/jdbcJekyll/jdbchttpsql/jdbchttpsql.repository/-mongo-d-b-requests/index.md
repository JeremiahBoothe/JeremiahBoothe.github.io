//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[MongoDBRequests](index.md)

# MongoDBRequests

class [MongoDBRequests](index.md)

This class handles operations related to MongoDB such as initializing the client, ensuring the collection exists, inserting data, and closing the client connection.

#### Parameters

jvm

| | |
|---|---|
| mongoDBConnectionData | The connection data required to establish a connection to MongoDB. |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>fun [close](close.md)()<br>Closes the MongoDB client connection. |
| [ensureCollectionExists](ensure-collection-exists.md) | [jvm]<br>fun [ensureCollectionExists](ensure-collection-exists.md)()<br>Ensures that the MongoDB collection exists. |
| [insertSongData](insert-song-data.md) | [jvm]<br>fun [insertSongData](insert-song-data.md)(songData: [SongData](../../jdbchttpsql.data/-song-data/index.md))<br>Inserts the given song data into the MongoDB collection. |
