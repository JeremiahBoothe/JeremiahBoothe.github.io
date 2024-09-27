//[jdbchttpsql](../../../index.md)/[jdbchttpsql.encrypt](../index.md)/[EncryptDecrypt](index.md)/[decryptWithAES](decrypt-with-a-e-s.md)

# decryptWithAES

[jvm]\
fun [decryptWithAES](decrypt-with-a-e-s.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), strToDecrypt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?

Decrypts the given string using AES encryption with the provided key.

#### Return

the decrypted string, or null if an error occurs during decryption.

#### Parameters

jvm

| | |
|---|---|
| key | the AES key used for decryption. |
| strToDecrypt | the string to be decrypted. |
