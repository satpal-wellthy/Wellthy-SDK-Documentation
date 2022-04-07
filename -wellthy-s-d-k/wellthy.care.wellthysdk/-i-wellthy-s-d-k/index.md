---
title: IWellthySDK
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)



# IWellthySDK



[androidJvm]\
interface [IWellthySDK](index.html)

This is interface for public methods of sdk that can be used by third party apps.



## Functions


| Name | Summary |
|---|---|
| [autoIntegrate](auto-integrate.html) | [androidJvm]<br>abstract fun [autoIntegrate](auto-integrate.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[ValidateSDKResponse](../../wellthy.care.wellthysdk.data/-validate-s-d-k-response/index.html)&gt;<br>Method to initialize and auto integrate Wellthy SDK. To be called in onCreate |
| [login](login.html) | [androidJvm]<br>abstract fun [login](login.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html)&gt;<br>Method to login an already registered patient on wellthy platform |
| [logout](logout.html) | [androidJvm]<br>abstract fun [logout](logout.html)()<br>Method to unregister Wellthy SDK. To be called on App logout |
| [register](register.html) | [androidJvm]<br>abstract fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html)&gt;<br>Method to register a patient on wellthy. To be called only if the user is not registered else |


## Inheritors


| Name |
|---|
| [WellthySDK](../-wellthy-s-d-k/index.html) |

