---
title: register
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[register](register.html)



# register



[androidJvm]\
abstract fun [register](register.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, age: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weight: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)? = null, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, height: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html)&gt;



Method to register a patient on wellthy. To be called only if the user is not registered else



#### Return



returns live data which will give



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.IWellthySDK](login.html) |  |
| [wellthy.care.wellthysdk.data.RegisterAPIResponse](../../wellthy.care.wellthysdk.data/-register-a-p-i-response/index.html) |  |



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



