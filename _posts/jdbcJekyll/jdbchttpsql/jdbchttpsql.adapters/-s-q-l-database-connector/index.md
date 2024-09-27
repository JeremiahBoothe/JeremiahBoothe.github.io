//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[SQLDatabaseConnector](index.md)

# SQLDatabaseConnector

class [SQLDatabaseConnector](index.md)&lt;[T](index.md) : [ConnectionData](../../jdbchttpsql.data/-connection-data/index.md)&gt;(connectionData: [T](index.md)) : [ConnectionData](../../jdbchttpsql.data/-connection-data/index.md)

A class that facilitates connecting to a SQL database using the provided connection data.

#### Parameters

jvm

| | |
|---|---|
| T | The type of connection data, extending from [ConnectionData](../../jdbchttpsql.data/-connection-data/index.md). |

#### Throws

| | |
|---|---|
| [IllegalArgumentException](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-illegal-argument-exception/index.html) | If the connection data type is unsupported. |

## Constructors

| | |
|---|---|
| [SQLDatabaseConnector](-s-q-l-database-connector.md) | [jvm]<br>constructor(connectionData: [T](index.md)) |

## Properties

| Name | Summary |
|---|---|
| [driverClassName](../../jdbchttpsql.data/-connection-data/driver-class-name.md) | [jvm]<br>open override val [driverClassName](../../jdbchttpsql.data/-connection-data/driver-class-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The class name of the JDBC or other relevant driver for the connection. |
| [ipAddress](../../jdbchttpsql.data/-connection-data/ip-address.md) | [jvm]<br>open override val [ipAddress](../../jdbchttpsql.data/-connection-data/ip-address.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The IP address and port number of the database server. |
| [password](../../jdbchttpsql.data/-connection-data/password.md) | [jvm]<br>open override val [password](../../jdbchttpsql.data/-connection-data/password.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The password used for authentication with the database. |
| [targetDatabase](../../jdbchttpsql.data/-connection-data/target-database.md) | [jvm]<br>open override val [targetDatabase](../../jdbchttpsql.data/-connection-data/target-database.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the target database to connect to. |
| [urlDriver](../../jdbchttpsql.data/-connection-data/url-driver.md) | [jvm]<br>open override val [urlDriver](../../jdbchttpsql.data/-connection-data/url-driver.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The URL driver string used to initiate the connection. |
| [userName](../../jdbchttpsql.data/-connection-data/user-name.md) | [jvm]<br>open override val [userName](../../jdbchttpsql.data/-connection-data/user-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The username used for authentication with the database. |

## Functions

| Name | Summary |
|---|---|
| [connectToDatabase](connect-to-database.md) | [jvm]<br>fun [connectToDatabase](connect-to-database.md)(): Database |
