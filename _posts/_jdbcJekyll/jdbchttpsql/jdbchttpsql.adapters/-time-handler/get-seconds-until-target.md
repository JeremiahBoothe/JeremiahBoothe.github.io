//[jdbchttpsql](../../../index.md)/[jdbchttpsql.adapters](../index.md)/[TimeHandler](index.md)/[getSecondsUntilTarget](get-seconds-until-target.md)

# getSecondsUntilTarget

[jvm]\
fun [getSecondsUntilTarget](get-seconds-until-target.md)(targetTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)

Calculates the number of seconds from the current time to a specified target time.

#### Return

The number of seconds remaining until the target time. If the target time is in the past, the result will be negative.

#### Parameters

jvm

| | |
|---|---|
| targetTime | The ZonedDateTime instance representing the target time. |
