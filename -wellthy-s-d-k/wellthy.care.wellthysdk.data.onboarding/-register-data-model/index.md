---
title: RegisterDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[RegisterDataModel](index.html)



# RegisterDataModel



[androidJvm]\
data class [RegisterDataModel](index.html)(country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, weight_unit: [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height_unit: [HeightUnit](../-height-unit/index.html)?, campaign_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

*IMPORTANT UPDATE* Changed to Model class Data class to enter mandatory and optional data for Register function



#### Return



RegisterDataModel object



## See also


androidJvm

| | |
|---|---|
| login |  |
| register |  |
| [wellthy.care.wellthysdk.data.diary.WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.HeightUnit](../-height-unit/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| country_code | Country ISD code eg (+91/91 for India): mandatory |
| phone | phone no of user: mandatory |
| name | name of user: mandatory |
| deviceId | device id: unique device identifier: optional |
| dob | dob: pass dob in YYYY-MM-dd format: optional |
| weight | weight: Int:  optional |
| weight_unit | WeightUnit : "kg" / "lbs": optional |
| height | height: optional |
| height_unit | HeightUnit : "cm" / "feet" : optional |
| campaign_id | Campaign Id to activate the patient therapy: Optional : If not provided it will activate the default therapy |



## Constructors


| | |
|---|---|
| [RegisterDataModel](-register-data-model.html) | [androidJvm]<br>fun [RegisterDataModel](-register-data-model.html)(country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, weight_unit: [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height_unit: [HeightUnit](../-height-unit/index.html)? = null, campaign_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [campaign_id](campaign_id.html) | [androidJvm]<br>var [campaign_id](campaign_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [country_code](country_code.html) | [androidJvm]<br>var [country_code](country_code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [deviceId](device-id.html) | [androidJvm]<br>var [deviceId](device-id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [dob](dob.html) | [androidJvm]<br>var [dob](dob.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [height](height.html) | [androidJvm]<br>var [height](height.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [height_unit](height_unit.html) | [androidJvm]<br>var [height_unit](height_unit.html): [HeightUnit](../-height-unit/index.html)? = null |
| [name](name.html) | [androidJvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [phone](phone.html) | [androidJvm]<br>var [phone](phone.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [weight](weight.html) | [androidJvm]<br>var [weight](weight.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [weight_unit](weight_unit.html) | [androidJvm]<br>var [weight_unit](weight_unit.html): [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)? = null |

