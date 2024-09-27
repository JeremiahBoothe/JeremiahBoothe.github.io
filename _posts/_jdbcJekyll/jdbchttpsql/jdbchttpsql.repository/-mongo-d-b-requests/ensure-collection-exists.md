//[jdbchttpsql](../../../index.md)/[jdbchttpsql.repository](../index.md)/[MongoDBRequests](index.md)/[ensureCollectionExists](ensure-collection-exists.md)

# ensureCollectionExists

[jvm]\
fun [ensureCollectionExists](ensure-collection-exists.md)()

Ensures that the MongoDB collection exists.

This method checks if any documents exist in the MongoDB collection. If no documents are found, it logs that the collection has been created. MongoDB typically creates collections automatically upon the first insert, so this is mainly a verification step.

Logs an informational message when the collection is confirmed to exist or is created.
