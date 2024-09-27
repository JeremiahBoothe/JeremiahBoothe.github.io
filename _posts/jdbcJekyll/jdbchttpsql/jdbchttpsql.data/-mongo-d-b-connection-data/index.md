//[jdbchttpsql](../../../index.md)/[jdbchttpsql.data](../index.md)/[MongoDBConnectionData](index.md)

# MongoDBConnectionData

[jvm]\
@Serializable

data class [MongoDBConnectionData](index.md)(val urlDriver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;mongodb://&quot;, val ipAddress: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;192.168.1.185:27017&quot;, val targetDatabase: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;JBTestMongoDB&quot;, val driverClassName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;&quot;, val userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().userName, var password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().password) : [ConnectionData](../-connection-data/index.md)

Data class representing the connection parameters required to establish a connection with a MongoDB database.

This class implements the [ConnectionData](../-connection-data/index.md) interface and provides specific default values for MongoDB.

## Constructors

| | |
|---|---|
| [MongoDBConnectionData](-mongo-d-b-connection-data.md) | [jvm]<br>constructor(urlDriver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;mongodb://&quot;, ipAddress: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;192.168.1.185:27017&quot;, targetDatabase: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;JBTestMongoDB&quot;, driverClassName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;&quot;, userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().userName, password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().password) |

## Properties

| Name | Summary |
|---|---|
| [driverClassName](driver-class-name.md) | [jvm]<br>open override val [driverClassName](driver-class-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The class name of the JDBC or other relevant driver for the MongoDB connection. Defaults to an empty string. |
| [ipAddress](ip-address.md) | [jvm]<br>open override val [ipAddress](ip-address.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The IP address and port number of the MongoDB server. Defaults to &quot;192.168.1.185:27017&quot;. |
| [password](password.md) | [jvm]<br>open override var [password](password.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The password used for authentication with the MongoDB database, loaded from a credentials file. |
| [targetDatabase](target-database.md) | [jvm]<br>open override val [targetDatabase](target-database.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the target MongoDB database to connect to. Defaults to &quot;JBTestMongoDB&quot;. |
| [urlDriver](url-driver.md) | [jvm]<br>open override val [urlDriver](url-driver.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The URL driver string used to initiate the MongoDB connection. Defaults to &quot;mongodb://&quot;. |
| [userName](user-name.md) | [jvm]<br>open override val [userName](user-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The username used for authentication with the MongoDB database, loaded from a credentials file. |
