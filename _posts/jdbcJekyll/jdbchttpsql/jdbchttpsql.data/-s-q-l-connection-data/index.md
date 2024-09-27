//[jdbchttpsql](../../../index.md)/[jdbchttpsql.data](../index.md)/[SQLConnectionData](index.md)

# SQLConnectionData

[jvm]\
@Serializable

data class [SQLConnectionData](index.md)(val urlDriver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;jdbc:mysql://&quot;, val ipAddress: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;192.168.1.185:3306&quot;, val targetDatabase: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;JBTestQL&quot;, val driverClassName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;com.mysql.cj.jdbc.Driver&quot;, val userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().userName, val password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().password) : [ConnectionData](../-connection-data/index.md)

Data class representing the essential data required for establishing an SQL database connection.

This class provides the necessary parameters to connect to an SQL database, including the URL driver, IP address, target database, driver class name, username, and password. It implements the [ConnectionData](../-connection-data/index.md) interface and acts as a concrete implementation specifically for SQL databases.

## Constructors

| | |
|---|---|
| [SQLConnectionData](-s-q-l-connection-data.md) | [jvm]<br>constructor(urlDriver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;jdbc:mysql://&quot;, ipAddress: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;192.168.1.185:3306&quot;, targetDatabase: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;JBTestQL&quot;, driverClassName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = &quot;com.mysql.cj.jdbc.Driver&quot;, userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().userName, password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = loadUserInfoFromFile().password) |

## Properties

| Name | Summary |
|---|---|
| [driverClassName](driver-class-name.md) | [jvm]<br>open override val [driverClassName](driver-class-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The fully qualified name of the JDBC driver class. Defaults to &quot;com.mysql.cj.jdbc.Driver&quot;. |
| [ipAddress](ip-address.md) | [jvm]<br>open override val [ipAddress](ip-address.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The IP address and port number of the database server. Defaults to &quot;192.168.1.185:3306&quot;. |
| [password](password.md) | [jvm]<br>open override val [password](password.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The password for authenticating the connection, loaded from a credentials file. |
| [targetDatabase](target-database.md) | [jvm]<br>open override val [targetDatabase](target-database.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the database to connect to. Defaults to &quot;JBTestQL&quot;. |
| [urlDriver](url-driver.md) | [jvm]<br>open override val [urlDriver](url-driver.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The JDBC URL prefix used to establish the connection. Defaults to &quot;jdbc:mysql://&quot;. |
| [userName](user-name.md) | [jvm]<br>open override val [userName](user-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The username for authenticating the connection, loaded from a credentials file. |
