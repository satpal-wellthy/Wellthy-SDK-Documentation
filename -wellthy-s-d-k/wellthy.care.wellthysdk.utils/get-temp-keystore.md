---
title: getTempKeystore
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.utils](index.html)/[getTempKeystore](get-temp-keystore.html)



# getTempKeystore



[androidJvm]\
fun [getTempKeystore](get-temp-keystore.html)(customerKeystore: [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html), certId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), customerKeystorePassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)



Create an in-memory keystore from the keystore on the filesystem.



#### Return



a temporary keystore with the certificate and key aliases and password normalized for IoTSslHelper.



## Parameters


androidJvm

| | |
|---|---|
| customerKeystore | the keystore provided by the customer. |
| certId | the certificate / key aliases in the keystore. |
| customerKeystorePassword | the password for the keystore. |




