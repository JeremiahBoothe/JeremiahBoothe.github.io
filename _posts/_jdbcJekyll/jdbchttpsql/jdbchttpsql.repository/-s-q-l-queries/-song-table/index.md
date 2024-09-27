//[jdbchttpsql](../../../../index.md)/[jdbchttpsql.repository](../../index.md)/[SQLQueries](../index.md)/[SongTable](index.md)

# SongTable

[jvm]\
object [SongTable](index.md) : Table&lt;[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)&gt; 

Represents the database table structure for storing song metadata. The table is named &quot;metadata&quot; and contains various columns for song data.

## Properties

| Name | Summary |
|---|---|
| [album](album.md) | [jvm]<br>val [album](album.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [alias](index.md#643768950%2FProperties%2F-1216412040) | [jvm]<br>val [alias](index.md#643768950%2FProperties%2F-1216412040): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [artist](artist.md) | [jvm]<br>val [artist](artist.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [catalog](index.md#1462050445%2FProperties%2F-1216412040) | [jvm]<br>val [catalog](index.md#1462050445%2FProperties%2F-1216412040): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [columns](index.md#2120772425%2FProperties%2F-1216412040) | [jvm]<br>val [columns](index.md#2120772425%2FProperties%2F-1216412040): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Column&lt;*&gt;&gt; |
| [createdAt](created-at.md) | [jvm]<br>val [createdAt](created-at.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [endsAt](ends-at.md) | [jvm]<br>val [endsAt](ends-at.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [entityClass](index.md#-154271151%2FProperties%2F-1216412040) | [jvm]<br>val [entityClass](index.md#-154271151%2FProperties%2F-1216412040): [KClass](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-class/index.html)&lt;[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)&gt;? |
| [genre](genre.md) | [jvm]<br>val [genre](genre.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [id](id.md) | [jvm]<br>val [id](id.md): Column&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [length](length.md) | [jvm]<br>val [length](length.md): Column&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [primaryKeys](index.md#641857968%2FProperties%2F-1216412040) | [jvm]<br>val [primaryKeys](index.md#641857968%2FProperties%2F-1216412040): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;Column&lt;*&gt;&gt; |
| [referencedKotlinType](index.md#1580874516%2FProperties%2F-1216412040) | [jvm]<br>val [referencedKotlinType](index.md#1580874516%2FProperties%2F-1216412040): [KType](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-type/index.html) |
| [referencedType](index.md#-1165976043%2FProperties%2F-1216412040) | [jvm]<br>val [referencedType](index.md#-1165976043%2FProperties%2F-1216412040): [Type](https://docs.oracle.com/javase/8/docs/api/java/lang/reflect/Type.html) |
| [releaseyear](releaseyear.md) | [jvm]<br>val [releaseyear](releaseyear.md): Column&lt;[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)&gt; |
| [schema](index.md#-1779279021%2FProperties%2F-1216412040) | [jvm]<br>val [schema](index.md#-1779279021%2FProperties%2F-1216412040): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [startedAt](started-at.md) | [jvm]<br>val [startedAt](started-at.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [tableName](index.md#-1061132051%2FProperties%2F-1216412040) | [jvm]<br>val [tableName](index.md#-1061132051%2FProperties%2F-1216412040): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [title](title.md) | [jvm]<br>val [title](title.md): Column&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

## Functions

| Name | Summary |
|---|---|
| [aliased](index.md#1316499710%2FFunctions%2F-1216412040) | [jvm]<br>open override fun [aliased](index.md#1316499710%2FFunctions%2F-1216412040)(alias: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Table&lt;[Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)&gt; |
| [asExpression](index.md#-1780546710%2FFunctions%2F-1216412040) | [jvm]<br>open fun [asExpression](index.md#-1780546710%2FFunctions%2F-1216412040)(): TableExpression |
| [bindTo](index.md#866257180%2FFunctions%2F-1216412040) | [jvm]<br>inline fun &lt;[C](index.md#866257180%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; Column&lt;[C](index.md#866257180%2FFunctions%2F-1216412040)&gt;.[bindTo](index.md#866257180%2FFunctions%2F-1216412040)(selector: ([Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)) -&gt; [C](index.md#866257180%2FFunctions%2F-1216412040)?): Column&lt;[C](index.md#866257180%2FFunctions%2F-1216412040)&gt; |
| [createEntity](index.md#-1519680417%2FFunctions%2F-1216412040) | [jvm]<br>fun [createEntity](index.md#-1519680417%2FFunctions%2F-1216412040)(row: QueryRowSet, withReferences: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html) |
| [equals](index.md#49267181%2FFunctions%2F-1216412040) | [jvm]<br>operator override fun [equals](index.md#49267181%2FFunctions%2F-1216412040)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [get](index.md#-353756012%2FFunctions%2F-1216412040) | [jvm]<br>operator fun [get](index.md#-353756012%2FFunctions%2F-1216412040)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): Column&lt;*&gt; |
| [hashCode](index.md#-331409319%2FFunctions%2F-1216412040) | [jvm]<br>override fun [hashCode](index.md#-331409319%2FFunctions%2F-1216412040)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [primaryKey](index.md#525735072%2FFunctions%2F-1216412040) | [jvm]<br>fun &lt;[C](index.md#525735072%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; Column&lt;[C](index.md#525735072%2FFunctions%2F-1216412040)&gt;.[primaryKey](index.md#525735072%2FFunctions%2F-1216412040)(): Column&lt;[C](index.md#525735072%2FFunctions%2F-1216412040)&gt; |
| [references](index.md#2035001590%2FFunctions%2F-1216412040) | [jvm]<br>inline fun &lt;[C](index.md#2035001590%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](index.md#2035001590%2FFunctions%2F-1216412040) : Entity&lt;[R](index.md#2035001590%2FFunctions%2F-1216412040)&gt;&gt; Column&lt;[C](index.md#2035001590%2FFunctions%2F-1216412040)&gt;.[references](index.md#2035001590%2FFunctions%2F-1216412040)(referenceTable: Table&lt;[R](index.md#2035001590%2FFunctions%2F-1216412040)&gt;, selector: ([Nothing](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-nothing/index.html)) -&gt; [R](index.md#2035001590%2FFunctions%2F-1216412040)?): Column&lt;[C](index.md#2035001590%2FFunctions%2F-1216412040)&gt; |
| [registerColumn](index.md#-1907218187%2FFunctions%2F-1216412040) | [jvm]<br>fun &lt;[C](index.md#-1907218187%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; [registerColumn](index.md#-1907218187%2FFunctions%2F-1216412040)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), sqlType: SqlType&lt;[C](index.md#-1907218187%2FFunctions%2F-1216412040)&gt;): Column&lt;[C](index.md#-1907218187%2FFunctions%2F-1216412040)&gt; |
| [toString](index.md#-509575384%2FFunctions%2F-1216412040) | [jvm]<br>open override fun [toString](index.md#-509575384%2FFunctions%2F-1216412040)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [transform](index.md#675323752%2FFunctions%2F-1216412040) | [jvm]<br>fun &lt;[C](index.md#675323752%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [R](index.md#675323752%2FFunctions%2F-1216412040) : [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)&gt; Column&lt;[C](index.md#675323752%2FFunctions%2F-1216412040)&gt;.[transform](index.md#675323752%2FFunctions%2F-1216412040)(fromUnderlyingValue: ([C](index.md#675323752%2FFunctions%2F-1216412040)) -&gt; [R](index.md#675323752%2FFunctions%2F-1216412040), toUnderlyingValue: ([R](index.md#675323752%2FFunctions%2F-1216412040)) -&gt; [C](index.md#675323752%2FFunctions%2F-1216412040)): Column&lt;[R](index.md#675323752%2FFunctions%2F-1216412040)&gt; |
