---
title: BloodSugarLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[BloodSugarLogDataModel](index.html)



# BloodSugarLogDataModel



[androidJvm]\
data class [BloodSugarLogDataModel](index.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [BloodSugarUnit](../-blood-sugar-unit/index.html), meal_type: [BloodSugarMealType](../-blood-sugar-meal-type/index.html), blood_sugar_log_type: [BloodSugarLogType](../-blood-sugar-log-type/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [BloodSugarMood](../-blood-sugar-mood/index.html)?)

Data class to enter data for addBloodSugarLog and updateBloodSugarLog function



#### Return



BloodSugarLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.BloodSugarUnit](../-blood-sugar-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.BloodSugarMood](../-blood-sugar-mood/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.BloodSugarLogType](../-blood-sugar-log-type/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| value | : Double, |
| meal_type | : BloodSugarMealType (Breakfast, Lunch, Snacks, Dinner, Fasting, Random), |
| blood_sugar_log_type | : BloodSugarLogType (Pre Meal, Post Meal), |
| unit | : BloodSugarUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : BloodSugarMood? = null |



## Constructors


| | |
|---|---|
| [BloodSugarLogDataModel](-blood-sugar-log-data-model.html) | [androidJvm]<br>fun [BloodSugarLogDataModel](-blood-sugar-log-data-model.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [BloodSugarUnit](../-blood-sugar-unit/index.html), meal_type: [BloodSugarMealType](../-blood-sugar-meal-type/index.html), blood_sugar_log_type: [BloodSugarLogType](../-blood-sugar-log-type/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [BloodSugarMood](../-blood-sugar-mood/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [blood_sugar_log_type](blood_sugar_log_type.html) | [androidJvm]<br>var [blood_sugar_log_type](blood_sugar_log_type.html): [BloodSugarLogType](../-blood-sugar-log-type/index.html) |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [meal_type](meal_type.html) | [androidJvm]<br>var [meal_type](meal_type.html): [BloodSugarMealType](../-blood-sugar-meal-type/index.html) |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [BloodSugarMood](../-blood-sugar-mood/index.html)? = null |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [BloodSugarUnit](../-blood-sugar-unit/index.html) |
| [value](value.html) | [androidJvm]<br>var [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

