//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[TimeHandler](index.md)/[updateTargetTime](update-target-time.md)

# updateTargetTime

[jvm]\
fun [updateTargetTime](update-target-time.md)(currentTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html), durationInSeconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html)

Updates the target time by adding a specified duration in seconds to the current time.

#### Return

A ZonedDateTime object representing the updated target time.

#### Parameters

jvm

| | |
|---|---|
| currentTime | The current ZonedDateTime instance from which the update will be made. |
| durationInSeconds | The duration in seconds to be added to the current time. |
