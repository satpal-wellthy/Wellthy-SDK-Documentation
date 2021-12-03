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
| [authSDK](auth-s-d-k.html) | [androidJvm]<br>abstract fun [authSDK](auth-s-d-k.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[ValidateSDKResponse](../../wellthy.care.wellthysdk.data/-validate-s-d-k-response/index.html)&gt;<br>Method to initialize SDK |
| [logDiary](log-diary.html) | [androidJvm]<br>abstract fun [logDiary](log-diary.html)(data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Method to log in diary |
| [register](register.html) | [androidJvm]<br>abstract fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterResponse](../../wellthy.care.wellthysdk.data/-register-response/index.html)&gt;<br>Method to onboard a patient on wellthy platform |


## Inheritors


| Name |
|---|
| [WellthySDK](../-wellthy-s-d-k/index.html) |

