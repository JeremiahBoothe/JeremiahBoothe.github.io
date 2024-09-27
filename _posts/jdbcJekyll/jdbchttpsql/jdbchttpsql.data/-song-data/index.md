//[jdbchttpsql](../../../index.md)/[jdbchttpsql.data](../index.md)/[SongData](index.md)

# SongData

[jvm]\
@Serializable

data class [SongData](index.md)(val id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), val type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val album: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, val genre: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val releaseyear: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, val created_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val artist: [Artist](../-artist/index.md)?, val started_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val ends_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

Represents metadata for a song, including details such as the song's ID, title, album, genre, and artist information.

## Constructors

| | |
|---|---|
| [SongData](-song-data.md) | [jvm]<br>constructor(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, album: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, length: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, genre: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, releaseyear: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, created_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, artist: [Artist](../-artist/index.md)?, started_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, ends_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |

## Properties

| Name | Summary |
|---|---|
| [album](album.md) | [jvm]<br>val [album](album.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The album to which the song belongs. |
| [artist](artist.md) | [jvm]<br>val [artist](artist.md): [Artist](../-artist/index.md)?<br>The artist who performed or created the song. |
| [created_at](created_at.md) | [jvm]<br>val [created_at](created_at.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The timestamp of when the song entry was created. |
| [ends_at](ends_at.md) | [jvm]<br>val [ends_at](ends_at.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The ending timestamp for when the song stopped playing. |
| [genre](genre.md) | [jvm]<br>val [genre](genre.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The genre of the song, if specified. |
| [id](id.md) | [jvm]<br>val [id](id.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>A unique identifier for the song. |
| [length](length.md) | [jvm]<br>val [length](length.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?<br>The length or duration of the song in seconds. |
| [releaseyear](releaseyear.md) | [jvm]<br>val [releaseyear](releaseyear.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?<br>The year the song was released. |
| [started_at](started_at.md) | [jvm]<br>val [started_at](started_at.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The starting timestamp for when the song began playing. |
| [title](title.md) | [jvm]<br>val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The title of the song. |
| [type](type.md) | [jvm]<br>val [type](type.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>The type or category of the song, if applicable. |
