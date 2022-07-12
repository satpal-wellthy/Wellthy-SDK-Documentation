---
title: getAmazonIotKeystore
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.utils](index.html)/[getAmazonIotKeystore](get-amazon-iot-keystore.html)



# getAmazonIotKeystore



[androidJvm]\
fun [Context](https://developer.android.com/reference/kotlin/android/content/Context.html).[getAmazonIotKeystore](get-amazon-iot-keystore.html)(certId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, keystoreName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, keyStorePassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)



Get certificate and private key from keystore on the file system. Retrieves the certificate and private key from the filesystem keystore and creates a temporary in-memory keystore to be used when connecting to service.



#### Return



KeyStore with private and public keys and certificate.



## Parameters


androidJvm

| | |
|---|---|
| certId | The certificate Id or alias. |
| keystoreName | The keystore filename. |
| keyStorePassword | The password for the keystore. |




