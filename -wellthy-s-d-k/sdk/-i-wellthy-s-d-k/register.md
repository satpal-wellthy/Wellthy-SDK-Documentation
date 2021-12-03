---
title: register
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[register](register.html)



# register



[androidJvm]\
abstract fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterResponse](../../wellthy.care.wellthysdk.data/-register-response/index.html)&gt;



Method to onboard a patient on wellthy platform



#### Return



returns live data which will give register api response



## Parameters


androidJvm

| | |
|---|---|
| countryCode | Country ISD code: mandatory field |
| phone | phone no of user: mandatory field |
| userName | name of user: mandatory field |
| deviceId | device id: optional field |
| age | age: optional field |
| weight | weight: optional field |
| weightUnit | weightUnit: optional field |
| height | height: optional field |
| heightUnit | heightUnit: optional field |



## Throws


| | |
|---|---|
|  |  |



