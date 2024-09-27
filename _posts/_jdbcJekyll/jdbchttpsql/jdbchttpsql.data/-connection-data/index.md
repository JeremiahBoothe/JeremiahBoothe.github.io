//[jdbchttpsql](../../../index.md)/[jdbchttpsql.data](../index.md)/[ConnectionData](index.md)

# ConnectionData

interface [ConnectionData](index.md)

Interface representing the essential data required for database connections.

Implement this interface to provide connection parameters for different types of databases, such as MongoDB or SQL databases. Various classes that require database connection information can utilize implementations of this interface to access the necessary connection details.

#### Inheritors

| |
|---|
| [MongoDBDatabaseConnector](../../jdbchttpsql.adapters/-mongo-d-b-database-connector/index.md) |
| [SQLDatabaseConnector](../../jdbchttpsql.adapters/-s-q-l-database-connector/index.md) |
| [MongoDBConnectionData](../-mongo-d-b-connection-data/index.md) |
| [SQLConnectionData](../-s-q-l-connection-data/index.md) |

## Properties

| Name | Summary |
|---|---|
| [driverClassName](driver-class-name.md) | [jvm]<br>abstract val [driverClassName](driver-class-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The class name of the JDBC or other relevant driver for the connection. |
| [ipAddress](ip-address.md) | [jvm]<br>abstract val [ipAddress](ip-address.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The IP address and port number of the database server. |
| [password](password.md) | [jvm]<br>abstract val [password](password.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The password used for authentication with the database. |
| [targetDatabase](target-database.md) | [jvm]<br>abstract val [targetDatabase](target-database.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the target database to connect to. |
| [urlDriver](url-driver.md) | [jvm]<br>abstract val [urlDriver](url-driver.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The URL driver string used to initiate the connection. |
| [userName](user-name.md) | [jvm]<br>abstract val [userName](user-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The username used for authentication with the database. |
