---
title: wellthy.care.wellthysdk.data.profile.you
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.data.profile.you](index.html)



# Package wellthy.care.wellthysdk.data.profile.you



## Types


| Name | Summary |
|---|---|
| [CareGiverDataModel](-care-giver-data-model/index.html) | [androidJvm]<br>data class [CareGiverDataModel](-care-giver-data-model/index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [Gender](-gender/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), relation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Data class to enter data for addCaregiver function : Add Care giver details ('Name', 'Email', DOB, gender etc) : all mandatory |
| [Gender](-gender/index.html) | [androidJvm]<br>enum [Gender](-gender/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[Gender](-gender/index.html)&gt; |
| [ProfileDataModel](-profile-data-model/index.html) | [androidJvm]<br>data class [ProfileDataModel](-profile-data-model/index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, gender: [Gender](-gender/index.html)?, weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, weight_unit: [WeightUnit](../wellthy.care.wellthysdk.data.diary/-weight-unit/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height_unit: [HeightUnit](../wellthy.care.wellthysdk.data.onboarding/-height-unit/index.html)?, mother_tongue: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, diet: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, eye_problem: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, blood_sugar_monitor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, gym_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, location_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, working_professional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, diabetic_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, hypertension_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)<br>Data class to enter data for updateProfile function : ('Name', 'Email', DOB, Mother Tongue etc) : all optional : Only update the required ones |

