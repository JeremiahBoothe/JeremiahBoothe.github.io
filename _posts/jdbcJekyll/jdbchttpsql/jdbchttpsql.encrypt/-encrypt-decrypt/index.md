//[jdbchttpsql](../../../index.md)/[jdbchttpsql.encrypt](../index.md)/[EncryptDecrypt](index.md)

# EncryptDecrypt

[jvm]\
class [EncryptDecrypt](index.md)

starting point to encrypt/decrypt tokens/passwords/account info for social media logins and database access. implementation from https://rrohaill.medium.com/aes-encryption-decryption-using-kotlin-7104e79f0f4d uses BouncyCastle https://www.bouncycastle.org/ implementation(&quot;org.bouncycastle:bcprov-jdk18on:1.76&quot;)

## Constructors

| | |
|---|---|
| [EncryptDecrypt](-encrypt-decrypt.md) | [jvm]<br>constructor() |

## Properties

| Name | Summary |
|---|---|
| [secretKey](secret-key.md) | [jvm]<br>val [secretKey](secret-key.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Secret Key Example |

## Functions

| Name | Summary |
|---|---|
| [decryptWithAES](decrypt-with-a-e-s.md) | [jvm]<br>fun [decryptWithAES](decrypt-with-a-e-s.md)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), strToDecrypt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>Decrypts the given string using AES encryption with the provided key. |
| [encrypt](encrypt.md) | [jvm]<br>fun [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html).[encrypt](encrypt.md)(strToEncrypt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?<br>Encrypts the given string using AES encryption with the provided key. |
