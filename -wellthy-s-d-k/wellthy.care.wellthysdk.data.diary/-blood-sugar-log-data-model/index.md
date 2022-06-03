---
title: BloodSugarLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[BloodSugarLogDataModel](index.html)



# BloodSugarLogDataModel



[androidJvm]\
data class [BloodSugarLogDataModel](index.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [BloodSugarUnit](../-blood-sugar-unit/index.html), mealType: [BloodSugarMealType](../-blood-sugar-meal-type/index.html), bloodSugarLogType: [BloodSugarLogType](../-blood-sugar-log-type/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [BloodSugarMoods](../-blood-sugar-moods/index.html)?)

Data class to enter data for addBloodSugarLog and updateBloodSugarLog function



#### Return



BloodSugarLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.BloodSugarUnit](../-blood-sugar-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.BloodSugarMoods](../-blood-sugar-moods/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.BloodSugarLogType](../-blood-sugar-log-type/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| value | : Double, |
| mealType | : BloodSugarMealType (Breakfast, Lunch, Snacks, Dinner, Fasting, Random), |
| bloodSugarLogType | : BloodSugarLogType (Pre Meal, Post Meal), |
| unit | : BloodSugarUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : BloodSugarMoods? = null |



## Constructors


| | |
|---|---|
| [BloodSugarLogDataModel](-blood-sugar-log-data-model.html) | [androidJvm]<br>fun [BloodSugarLogDataModel](-blood-sugar-log-data-model.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [BloodSugarUnit](../-blood-sugar-unit/index.html), mealType: [BloodSugarMealType](../-blood-sugar-meal-type/index.html), bloodSugarLogType: [BloodSugarLogType](../-blood-sugar-log-type/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [BloodSugarMoods](../-blood-sugar-moods/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [bloodSugarLogType](blood-sugar-log-type.html) | [androidJvm]<br>var [bloodSugarLogType](blood-sugar-log-type.html): [BloodSugarLogType](../-blood-sugar-log-type/index.html) |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mealType](meal-type.html) | [androidJvm]<br>var [mealType](meal-type.html): [BloodSugarMealType](../-blood-sugar-meal-type/index.html) |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [BloodSugarMoods](../-blood-sugar-moods/index.html)? = null |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [BloodSugarUnit](../-blood-sugar-unit/index.html) |
| [value](value.html) | [androidJvm]<br>var [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

