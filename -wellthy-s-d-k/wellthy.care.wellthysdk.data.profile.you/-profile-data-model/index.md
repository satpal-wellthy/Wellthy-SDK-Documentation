---
title: ProfileDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.profile.you](../index.html)/[ProfileDataModel](index.html)



# ProfileDataModel



[androidJvm]\
data class [ProfileDataModel](index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, gender: [Gender](../-gender/index.html)?, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, weight_unit: [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height_unit: [HeightUnit](../../wellthy.care.wellthysdk.data.onboarding/-height-unit/index.html)?, mother_tongue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, diet: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, eye_problem: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, blood_sugar_monitor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, gym_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, location_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, working_professional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, diabetic_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, hypertension_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

Data class to enter data for updateProfile function : ('Name', 'Email', DOB, Mother Tongue etc) : all optional : Only update the required ones



#### Return



ProfileDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.profile.you.Gender](../-gender/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.HeightUnit](../../wellthy.care.wellthysdk.data.onboarding/-height-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html) |  |
| updateProfile |  |



## Parameters


androidJvm

| | |
|---|---|
| name | : String? |
| dob | : String? pass dob in YYYY-MM-dd format: optional |
| email | : String? |
| gender | : Gender? |
| weight | : Int? |
| weight_unit | : WeightUnit? |
| height | : Int? |
| height_unit | : HeightUnit? |
| mother_tongue | : String? |
| diet | : String? |
| eye_problem | : Boolean? |
| blood_sugar_monitor | : Boolean? |
| gym_access | : Boolean? |
| location_access | : Boolean? |
| working_professional | : Boolean? |
| diabetic_since | : String? |
| hypertension_since | : String? |



## Constructors


| | |
|---|---|
| [ProfileDataModel](-profile-data-model.html) | [androidJvm]<br>fun [ProfileDataModel](-profile-data-model.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, gender: [Gender](../-gender/index.html)? = null, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, weight_unit: [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height_unit: [HeightUnit](../../wellthy.care.wellthysdk.data.onboarding/-height-unit/index.html)? = null, mother_tongue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, diet: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, eye_problem: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, blood_sugar_monitor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, gym_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, location_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, working_professional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, diabetic_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, hypertension_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [blood_sugar_monitor](blood_sugar_monitor.html) | [androidJvm]<br>var [blood_sugar_monitor](blood_sugar_monitor.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [diabetic_since](diabetic_since.html) | [androidJvm]<br>var [diabetic_since](diabetic_since.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [diet](diet.html) | [androidJvm]<br>var [diet](diet.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [dob](dob.html) | [androidJvm]<br>var [dob](dob.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [email](email.html) | [androidJvm]<br>var [email](email.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [eye_problem](eye_problem.html) | [androidJvm]<br>var [eye_problem](eye_problem.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [gender](gender.html) | [androidJvm]<br>var [gender](gender.html): [Gender](../-gender/index.html)? = null |
| [gym_access](gym_access.html) | [androidJvm]<br>var [gym_access](gym_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [height](height.html) | [androidJvm]<br>var [height](height.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [height_unit](height_unit.html) | [androidJvm]<br>var [height_unit](height_unit.html): [HeightUnit](../../wellthy.care.wellthysdk.data.onboarding/-height-unit/index.html)? = null |
| [hypertension_since](hypertension_since.html) | [androidJvm]<br>var [hypertension_since](hypertension_since.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_access](location_access.html) | [androidJvm]<br>var [location_access](location_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [mother_tongue](mother_tongue.html) | [androidJvm]<br>var [mother_tongue](mother_tongue.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [name](name.html) | [androidJvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [weight](weight.html) | [androidJvm]<br>var [weight](weight.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [weight_unit](weight_unit.html) | [androidJvm]<br>var [weight_unit](weight_unit.html): [WeightUnit](../../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)? = null |
| [working_professional](working_professional.html) | [androidJvm]<br>var [working_professional](working_professional.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |

