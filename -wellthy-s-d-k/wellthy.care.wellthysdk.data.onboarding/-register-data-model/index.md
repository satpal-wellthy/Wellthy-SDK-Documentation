---
title: RegisterDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[RegisterDataModel](index.html)



# RegisterDataModel



[androidJvm]\
data class [RegisterDataModel](index.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

*IMPORTANT UPDATE* Changed to Model class Data class to enter mandatory and optional data for Register function



#### Return



RegisterDataModel object



## See also


androidJvm

| | |
|---|---|
| login |  |
| register |  |



## Parameters


androidJvm

| | |
|---|---|
| countryCode | Country ISD code eg (+91/91 for India): mandatory |
| phone | phone no of user: mandatory |
| userName | name of user: optional |
| deviceId | device id: unique device identifier: optional |
| dob | dob: pass dob in YYYY-MM-dd format: optional |
| weight | weight: Int:  optional |
| weightUnit | weightUnit : "kg" / "lbs": optional |
| height | height: optional |
| heightUnit | heightUnit : "cm" / "ft" : optional |



## Constructors


| | |
|---|---|
| [RegisterDataModel](-register-data-model.html) | [androidJvm]<br>fun [RegisterDataModel](-register-data-model.html)(countryCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", userName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, weightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, heightUnit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [countryCode](country-code.html) | [androidJvm]<br>var [countryCode](country-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [deviceId](device-id.html) | [androidJvm]<br>var [deviceId](device-id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [dob](dob.html) | [androidJvm]<br>var [dob](dob.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [height](height.html) | [androidJvm]<br>var [height](height.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [heightUnit](height-unit.html) | [androidJvm]<br>var [heightUnit](height-unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [phone](phone.html) | [androidJvm]<br>var [phone](phone.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [userName](user-name.html) | [androidJvm]<br>var [userName](user-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [weight](weight.html) | [androidJvm]<br>var [weight](weight.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [weightUnit](weight-unit.html) | [androidJvm]<br>var [weightUnit](weight-unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |

