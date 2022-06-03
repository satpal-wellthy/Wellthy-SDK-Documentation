---
title: ActivityLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[ActivityLogDataModel](index.html)



# ActivityLogDataModel



[androidJvm]\
data class [ActivityLogDataModel](index.html)(activity_type: [ActivityType](../-activity-type/index.html), unit: [ActivityUnit](../-activity-unit/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), steps_count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [ActivityMoods](../-activity-moods/index.html)?)

Data class to enter data for addActivityLog and updateActivityLog function



#### Return



ActivityLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.ActivityType](../-activity-type/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.ActivityMoods](../-activity-moods/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.ActivityUnit](../-activity-unit/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| activity_type | : ActivityType, |
| unit | : ActivityUnit, |
| value | : Double, |
| steps_count | : Int? = null, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : ActivityMoods? = null |



## Constructors


| | |
|---|---|
| [ActivityLogDataModel](-activity-log-data-model.html) | [androidJvm]<br>fun [ActivityLogDataModel](-activity-log-data-model.html)(activity_type: [ActivityType](../-activity-type/index.html), unit: [ActivityUnit](../-activity-unit/index.html), value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), steps_count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [ActivityMoods](../-activity-moods/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [activity_type](activity_type.html) | [androidJvm]<br>var [activity_type](activity_type.html): [ActivityType](../-activity-type/index.html) |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [ActivityMoods](../-activity-moods/index.html)? = null |
| [steps_count](steps_count.html) | [androidJvm]<br>var [steps_count](steps_count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [ActivityUnit](../-activity-unit/index.html) |
| [value](value.html) | [androidJvm]<br>var [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

