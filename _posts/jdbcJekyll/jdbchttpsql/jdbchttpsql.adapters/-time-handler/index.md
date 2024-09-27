//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[TimeHandler](index.md)

# TimeHandler

[jvm]\
class [TimeHandler](index.md)(formatter: [DateTimeFormatter](https://docs.oracle.com/javase/8/docs/api/java/time/format/DateTimeFormatter.html))

A utility class for handling time-related operations such as parsing target times, calculating the duration until a target time, and updating target times by a specified duration.

## Constructors

| | |
|---|---|
| [TimeHandler](-time-handler.md) | [jvm]<br>constructor(formatter: [DateTimeFormatter](https://docs.oracle.com/javase/8/docs/api/java/time/format/DateTimeFormatter.html)) |

## Functions

| Name | Summary |
|---|---|
| [getSecondsUntilTarget](get-seconds-until-target.md) | [jvm]<br>fun [getSecondsUntilTarget](get-seconds-until-target.md)(targetTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Calculates the number of seconds from the current time to a specified target time. |
| [parseTargetTime](parse-target-time.md) | [jvm]<br>fun [parseTargetTime](parse-target-time.md)(targetTimeString: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html) |
| [updateTargetTime](update-target-time.md) | [jvm]<br>fun [updateTargetTime](update-target-time.md)(currentTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html), durationInSeconds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html)<br>Updates the target time by adding a specified duration in seconds to the current time. |
