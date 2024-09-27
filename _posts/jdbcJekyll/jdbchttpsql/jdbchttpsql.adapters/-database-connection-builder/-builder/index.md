//[jdbchttpsql](../../../../index.md)/[jdbchttpsql.adapters](../../index.md)/[DatabaseConnectionBuilder](../index.md)/[Builder](index.md)

# Builder

[jvm]\
data class [Builder](index.md)(connection: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, post: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null)

A builder class for creating instances of `DatabaseConnectionBuilder`. It allows the configuration of database connection parameters.

## Constructors

| | |
|---|---|
| [Builder](-builder.md) | [jvm]<br>constructor(connection: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, post: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |

## Functions

| Name | Summary |
|---|---|
| [randomBuild](random-build.md) | [jvm]<br>fun [randomBuild](random-build.md)(): [DatabaseConnectionBuilder](../index.md)<br>Configures and builds a `DatabaseConnectionBuilder` instance with default or provided values. If the parameters `connection` and `post` are not explicitly set, default values will be used. |
