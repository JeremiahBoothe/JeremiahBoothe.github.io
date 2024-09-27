//[jdbchttpsql](../../../index.md)/[jdbchttpsql.sources](../index.md)/[DatabaseSourceBuilder](index.md)

# DatabaseSourceBuilder

class [DatabaseSourceBuilder](index.md)&lt;[T](index.md) : [ConnectionData](../../jdbchttpsql.data/-connection-data/index.md)&gt;(connectionData: [T](index.md))

Builder class for constructing and accessing database connection details.

This class takes a type parameter [T](index.md) which must extend [ConnectionData](../../jdbchttpsql.data/-connection-data/index.md). It ensures that the essential connection details are accessible, such as the URL, driver, username, and password.

#### Parameters

jvm

| | |
|---|---|
| connectionData | An instance of [T](index.md) that provides the necessary connection parameters. |

## Constructors

| | |
|---|---|
| [DatabaseSourceBuilder](-database-source-builder.md) | [jvm]<br>constructor(connectionData: [T](index.md)) |

## Functions

| Name | Summary |
|---|---|
| [getDriver](get-driver.md) | [jvm]<br>fun [getDriver](get-driver.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getPassword](get-password.md) | [jvm]<br>fun [getPassword](get-password.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getUrl](get-url.md) | [jvm]<br>fun [getUrl](get-url.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getUser](get-user.md) | [jvm]<br>fun [getUser](get-user.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
