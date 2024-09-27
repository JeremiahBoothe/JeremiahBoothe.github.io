//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[UserInfo](index.md)

# UserInfo

[jvm]\
@Serializable

data class [UserInfo](index.md)(val userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Data class representing user information.

This class is used to serialize and deserialize user credentials, specifically the username and password. It is implemented using the `@Serializable` annotation to indicate that instances of this class can be serialized and deserialized using Kotlin serialization.

## Constructors

| | |
|---|---|
| [UserInfo](-user-info.md) | [jvm]<br>constructor(userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |

## Properties

| Name | Summary |
|---|---|
| [password](password.md) | [jvm]<br>val [password](password.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The password for user authentication. |
| [userName](user-name.md) | [jvm]<br>val [userName](user-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The username for user authentication. |
