---
title: WellthySDK
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[WellthySDK](index.html)



# WellthySDK



[androidJvm]\
object [WellthySDK](index.html) : [IWellthySDK](../-i-wellthy-s-d-k/index.html)



## Functions


| Name | Summary |
|---|---|
| [authSDK](auth-s-d-k.html) | [androidJvm]<br>open override fun [authSDK](auth-s-d-k.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[ValidateSDKResponse](../../wellthy.care.wellthysdk.data/-validate-s-d-k-response/index.html)&gt;<br>Method to initialize SDK |
| [cancelApiCalls](cancel-api-calls.html) | [androidJvm]<br>fun [cancelApiCalls](cancel-api-calls.html)() |
| [logDiary](log-diary.html) | [androidJvm]<br>open override fun [logDiary](log-diary.html)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Method to log in diary |
| [register](register.html) | [androidJvm]<br>open override fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)?, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)?, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterResponse](../../wellthy.care.wellthysdk.data/-register-response/index.html)&gt;<br>Method to onboard a patient on wellthy platform |

