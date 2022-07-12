---
title: wellthy.care.wellthysdk.utils
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.utils](index.html)



# Package wellthy.care.wellthysdk.utils



## Types


| Name | Summary |
|---|---|
| [Constants](-constants/index.html) | [androidJvm]<br>object [Constants](-constants/index.html) |
| [GoogleFitSyncingManager](-google-fit-syncing-manager/index.html) | [androidJvm]<br>class [GoogleFitSyncingManager](-google-fit-syncing-manager/index.html) |
| [IGoogleFitSyncingCallbacks](-i-google-fit-syncing-callbacks/index.html) | [androidJvm]<br>interface [IGoogleFitSyncingCallbacks](-i-google-fit-syncing-callbacks/index.html) |
| [WellthyPrefs](-wellthy-prefs/index.html) | [androidJvm]<br>object [WellthyPrefs](-wellthy-prefs/index.html) |


## Functions


| Name | Summary |
|---|---|
| [generateUniqueTrackId](generate-unique-track-id.html) | [androidJvm]<br>fun [Constants](-constants/index.html).[generateUniqueTrackId](generate-unique-track-id.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getAmazonIotKeystore](get-amazon-iot-keystore.html) | [androidJvm]<br>fun [Context](https://developer.android.com/reference/kotlin/android/content/Context.html).[getAmazonIotKeystore](get-amazon-iot-keystore.html)(certId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, keystoreName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, keyStorePassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)<br>Get certificate and private key from keystore on the file system. Retrieves the certificate and private key from the filesystem keystore and creates a temporary in-memory keystore to be used when connecting to service. |
| [getRandomString](get-random-string.html) | [androidJvm]<br>fun [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html).[getRandomString](get-random-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getTempKeystore](get-temp-keystore.html) | [androidJvm]<br>fun [getTempKeystore](get-temp-keystore.html)(customerKeystore: [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html), certId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), customerKeystorePassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)<br>Create an in-memory keystore from the keystore on the filesystem. |
| [keystoreContainsAliasRaw](keystore-contains-alias-raw.html) | [androidJvm]<br>fun [Context](https://developer.android.com/reference/kotlin/android/content/Context.html).[keystoreContainsAliasRaw](keystore-contains-alias-raw.html)(certId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keystoreName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), keystorePassword: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if a cert/key alias is present in a keystore. |
| [printSDKIdentifier](print-s-d-k-identifier.html) | [androidJvm]<br>fun [Constants](-constants/index.html).[printSDKIdentifier](print-s-d-k-identifier.html)() |

