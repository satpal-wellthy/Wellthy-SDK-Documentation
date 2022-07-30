---
title: RegisterDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[RegisterDataModel](index.html)/[RegisterDataModel](-register-data-model.html)



# RegisterDataModel



[androidJvm]\
fun [RegisterDataModel](-register-data-model.html)(country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", deviceId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, weight_unit: [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height_unit: [HeightUnit](../-height-unit/index.html)? = null, campaign_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "")



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
| campaign_id | Campaign Id to activate the patient therapy |




