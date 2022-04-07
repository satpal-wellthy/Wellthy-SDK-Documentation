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
| [autoIntegrate](auto-integrate.html) | [androidJvm]<br>open override fun [autoIntegrate](auto-integrate.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[ValidateSDKResponse](../../wellthy.care.wellthysdk.data/-validate-s-d-k-response/index.html)&gt;<br>Method to initialize and auto integrate Wellthy SDK. To be called in onCreate |
| [login](login.html) | [androidJvm]<br>open override fun [login](login.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html)&gt;<br>Method to login an already registered patient on wellthy platform |
| [logout](logout.html) | [androidJvm]<br>open override fun [logout](logout.html)()<br>Method to unregister Wellthy SDK. To be called on App logout |
| [register](register.html) | [androidJvm]<br>open override fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)?, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)?, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html)&gt;<br>Method to register a patient on wellthy. To be called only if the user is not registered else |

