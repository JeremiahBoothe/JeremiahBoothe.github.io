//[jdbchttpsql](../../../index.md)/[jdbchttpsql.data](../index.md)/[RetryHandler](index.md)

# RetryHandler

[jvm]\
class [RetryHandler](index.md)(logger: Logger)

A handler that manages retry logic based on a target time.

## Constructors

| | |
|---|---|
| [RetryHandler](-retry-handler.md) | [jvm]<br>constructor(logger: Logger) |

## Functions

| Name | Summary |
|---|---|
| [handleRetries](handle-retries.md) | [jvm]<br>suspend fun [handleRetries](handle-retries.md)(targetTime: [ZonedDateTime](https://docs.oracle.com/javase/8/docs/api/java/time/ZonedDateTime.html), timeHandler: [TimeHandler](../../jdbchttpsql.adapters/-time-handler/index.md)) |
