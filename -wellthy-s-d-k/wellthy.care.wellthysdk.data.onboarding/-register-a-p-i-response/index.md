---
title: RegisterAPIResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[RegisterAPIResponse](index.html)



# RegisterAPIResponse



[androidJvm]\
data class [RegisterAPIResponse](index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), therapy_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), therapy_start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), weight_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), language_data: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, therapy_end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), is_expired: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, expires_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), has_hc_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, is_deleted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, caregiver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), sdk_version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), therapy_data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), diabetic_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), eye_problem: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, location_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, blood_sugar_monitor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, gym_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, working_professional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)?, campaign_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Data class which gives the response for register and login functions



## Constructors


| | |
|---|---|
| [RegisterAPIResponse](-register-a-p-i-response.html) | [androidJvm]<br>fun [RegisterAPIResponse](-register-a-p-i-response.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", therapy_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", therapy_start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", dob: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", gender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", weight_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", weight: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, height_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", language_data: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, therapy_end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", is_expired: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, expires_at: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", has_hc_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, is_deleted: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, caregiver: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", sdk_version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", therapy_data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", diabetic_since: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", eye_problem: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, location_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, blood_sugar_monitor: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, gym_access: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, working_professional: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, campaign_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", country_code: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", phone: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "") |


## Properties


| Name | Summary |
|---|---|
| [blood_sugar_monitor](blood_sugar_monitor.html) | [androidJvm]<br>var [blood_sugar_monitor](blood_sugar_monitor.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [campaign_id](campaign_id.html) | [androidJvm]<br>var [campaign_id](campaign_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [caregiver](caregiver.html) | [androidJvm]<br>var [caregiver](caregiver.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [country_code](country_code.html) | [androidJvm]<br>var [country_code](country_code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [diabetic_since](diabetic_since.html) | [androidJvm]<br>var [diabetic_since](diabetic_since.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dob](dob.html) | [androidJvm]<br>var [dob](dob.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [email](email.html) | [androidJvm]<br>var [email](email.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [expires_at](expires_at.html) | [androidJvm]<br>var [expires_at](expires_at.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [eye_problem](eye_problem.html) | [androidJvm]<br>var [eye_problem](eye_problem.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [gender](gender.html) | [androidJvm]<br>var [gender](gender.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [gym_access](gym_access.html) | [androidJvm]<br>var [gym_access](gym_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [has_hc_access](has_hc_access.html) | [androidJvm]<br>var [has_hc_access](has_hc_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [height](height.html) | [androidJvm]<br>var [height](height.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [height_unit](height_unit.html) | [androidJvm]<br>var [height_unit](height_unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [id](id.html) | [androidJvm]<br>var [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [is_deleted](is_deleted.html) | [androidJvm]<br>var [is_deleted](is_deleted.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [is_expired](is_expired.html) | [androidJvm]<br>var [is_expired](is_expired.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [language_data](language_data.html) | [androidJvm]<br>var [language_data](language_data.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [location_access](location_access.html) | [androidJvm]<br>var [location_access](location_access.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |
| [name](name.html) | [androidJvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [phone](phone.html) | [androidJvm]<br>var [phone](phone.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [sdk_version](sdk_version.html) | [androidJvm]<br>var [sdk_version](sdk_version.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.html) | [androidJvm]<br>var [status](status.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_data](therapy_data.html) | [androidJvm]<br>var [therapy_data](therapy_data.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_end_date](therapy_end_date.html) | [androidJvm]<br>var [therapy_end_date](therapy_end_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_id](therapy_id.html) | [androidJvm]<br>var [therapy_id](therapy_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [therapy_start_date](therapy_start_date.html) | [androidJvm]<br>var [therapy_start_date](therapy_start_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [weight](weight.html) | [androidJvm]<br>var [weight](weight.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [weight_unit](weight_unit.html) | [androidJvm]<br>var [weight_unit](weight_unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [working_professional](working_professional.html) | [androidJvm]<br>var [working_professional](working_professional.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null |

