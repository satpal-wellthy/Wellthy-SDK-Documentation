---
title: RegisterAPIResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[RegisterAPIResponse](index.html)



# RegisterAPIResponse



[androidJvm]\
data class [RegisterAPIResponse](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), therapy_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), therapy_start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), weight_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), language_data: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, therapy_end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), is_free: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, has_activated_subscription: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, conditions: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), health_goals: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), is_patient_onboarded: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, is_expired: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, expires_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), is_active: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, has_hc_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, is_deleted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, timezone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), caregiver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Data class which gives the response for register and login functions



## Constructors


| | |
|---|---|
| [RegisterAPIResponse](-register-a-p-i-response.html) | [androidJvm]<br>fun [RegisterAPIResponse](-register-a-p-i-response.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", therapy_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", therapy_start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", weight_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", language_data: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, age: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, therapy_end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", is_free: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, has_activated_subscription: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, conditions: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", health_goals: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", is_patient_onboarded: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, is_expired: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, expires_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", is_active: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, has_hc_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, is_deleted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, timezone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", caregiver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "") |


## Properties


| Name | Summary |
|---|---|
| [age](age.html) | [androidJvm]<br>var [age](age.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [caregiver](caregiver.html) | [androidJvm]<br>var [caregiver](caregiver.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [conditions](conditions.html) | [androidJvm]<br>var [conditions](conditions.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dob](dob.html) | [androidJvm]<br>var [dob](dob.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [email](email.html) | [androidJvm]<br>var [email](email.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [expires_at](expires_at.html) | [androidJvm]<br>var [expires_at](expires_at.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [gender](gender.html) | [androidJvm]<br>var [gender](gender.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [has_activated_subscription](has_activated_subscription.html) | [androidJvm]<br>var [has_activated_subscription](has_activated_subscription.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [has_hc_access](has_hc_access.html) | [androidJvm]<br>var [has_hc_access](has_hc_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [health_goals](health_goals.html) | [androidJvm]<br>var [health_goals](health_goals.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [height](height.html) | [androidJvm]<br>var [height](height.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [height_unit](height_unit.html) | [androidJvm]<br>var [height_unit](height_unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [id](id.html) | [androidJvm]<br>var [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [is_active](is_active.html) | [androidJvm]<br>var [is_active](is_active.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [is_deleted](is_deleted.html) | [androidJvm]<br>var [is_deleted](is_deleted.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [is_expired](is_expired.html) | [androidJvm]<br>var [is_expired](is_expired.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [is_free](is_free.html) | [androidJvm]<br>var [is_free](is_free.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [is_patient_onboarded](is_patient_onboarded.html) | [androidJvm]<br>var [is_patient_onboarded](is_patient_onboarded.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [language_data](language_data.html) | [androidJvm]<br>var [language_data](language_data.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [name](name.html) | [androidJvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.html) | [androidJvm]<br>var [status](status.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_end_date](therapy_end_date.html) | [androidJvm]<br>var [therapy_end_date](therapy_end_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_id](therapy_id.html) | [androidJvm]<br>var [therapy_id](therapy_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_start_date](therapy_start_date.html) | [androidJvm]<br>var [therapy_start_date](therapy_start_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [timezone](timezone.html) | [androidJvm]<br>var [timezone](timezone.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [weight](weight.html) | [androidJvm]<br>var [weight](weight.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [weight_unit](weight_unit.html) | [androidJvm]<br>var [weight_unit](weight_unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

