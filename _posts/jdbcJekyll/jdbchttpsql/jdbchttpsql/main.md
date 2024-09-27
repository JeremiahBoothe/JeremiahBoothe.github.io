//[jdbchttpsql](../../index.md)/[jdbchttpsql](index.md)/[main](main.md)

# main

[jvm]\
fun [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;.[main](main.md)()

The main entry point for the application, executed within a coroutine scope enabled by runBlocking.

This method initializes the necessary database connectors, loggers, SQL queries, and periodically processes song data fetched from an external HTTP source and stores it in databases, re-checking the target time to determine the delay between fetches.

The process involves:

- 
   Connecting to SQL and MongoDB databases.
- 
   Creating necessary SQL tables if they do not exist.
- 
   Setting and updating target times for data fetching cycles.
- 
   Fetching and processing song data from an external HTTP source.
- 
   Handling potential exceptions and implementing a retry mechanism.

#### Author

Jeremiah Boothe

#### Receiver

Array<String> Command-line arguments for
