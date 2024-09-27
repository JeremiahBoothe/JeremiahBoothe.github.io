//[jdbchttpsql](../../index.md)/[jdbchttpsql.adapters](index.md)

# Package-level declarations

## Types

| Name | Summary |
|---|---|
| [DatabaseConnectionBuilder](-database-connection-builder/index.md) | [jvm]<br>class [DatabaseConnectionBuilder](-database-connection-builder/index.md)<br>A work in progress class, used to build instances of `DatabaseConnectionBuilder`. The builder class helps in building a `DatabaseConnectionBuilder` instance with specific configurations for a database connection. |
| [MongoDBDatabaseConnector](-mongo-d-b-database-connector/index.md) | [jvm]<br>class [MongoDBDatabaseConnector](-mongo-d-b-database-connector/index.md)&lt;[T](-mongo-d-b-database-connector/index.md) : [ConnectionData](../jdbchttpsql.data/-connection-data/index.md)&gt;(connectionData: [T](-mongo-d-b-database-connector/index.md)) : [ConnectionData](../jdbchttpsql.data/-connection-data/index.md)<br>A class responsible for establishing connections to a MongoDB database. |
| [SongProcessor](-song-processor/index.md) | [jvm]<br>class [SongProcessor](-song-processor/index.md)(bridge: [HttpDatabaseBridge](../jdbchttpsql.model/-http-database-bridge/index.md), logger: Logger)<br>A class that processes song data by interacting with both an HTTP database bridge and a logger. This class fetches song data, updates target times, and logs the progress. |
| [SQLDatabaseConnector](-s-q-l-database-connector/index.md) | [jvm]<br>class [SQLDatabaseConnector](-s-q-l-database-connector/index.md)&lt;[T](-s-q-l-database-connector/index.md) : [ConnectionData](../jdbchttpsql.data/-connection-data/index.md)&gt;(connectionData: [T](-s-q-l-database-connector/index.md)) : [ConnectionData](../jdbchttpsql.data/-connection-data/index.md)<br>A class that facilitates connecting to a SQL database using the provided connection data. |
| [TimeHandler](-time-handler/index.md) | [jvm]<br>class [TimeHandler](-time-handler/index.md)(formatter: [DateTimeFormatter](https://docs.oracle.com/javase/8/docs/api/java/time/format/DateTimeFormatter.html))<br>A utility class for handling time-related operations such as parsing target times, calculating the duration until a target time, and updating target times by a specified duration. |
| [UserInfo](-user-info/index.md) | [jvm]<br>@Serializable<br>data class [UserInfo](-user-info/index.md)(val userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Data class representing user information. |

## Functions

| Name | Summary |
|---|---|
| [loadUserInfoFromFile](load-user-info-from-file.md) | [jvm]<br>fun [loadUserInfoFromFile](load-user-info-from-file.md)(): [UserInfo](-user-info/index.md)<br>Loads user information from a specified JSON file. |
