---
title: BloodPressureLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[BloodPressureLogDataModel](index.html)



# BloodPressureLogDataModel



[androidJvm]\
data class [BloodPressureLogDataModel](index.html)(systolic: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), systolic_unit: [SystolicUnit](../-systolic-unit/index.html), diastolic: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), diastolic_unit: [DiastolicUnit](../-diastolic-unit/index.html), heart_rate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), heart_rate_unit: [HeartRateUnit](../-heart-rate-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [BloodPressureMood](../-blood-pressure-mood/index.html)?)

Data class to enter data for addBloodPressureLog and updateBloodPressureLog function



#### Return



BloodPressureLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.SystolicUnit](../-systolic-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.DiastolicUnit](../-diastolic-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.HeartRateUnit](../-heart-rate-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.BloodPressureMood](../-blood-pressure-mood/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| systolic | : Int, |
| systolic_unit | : SystolicUnit, |
| diastolic | : Int, |
| diastolic_unit | : DiastolicUnit, |
| heart_rate | : Int, |
| heart_rate_unit | : HeartRateUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : BloodPressureMood? = null |



## Constructors


| | |
|---|---|
| [BloodPressureLogDataModel](-blood-pressure-log-data-model.html) | [androidJvm]<br>fun [BloodPressureLogDataModel](-blood-pressure-log-data-model.html)(systolic: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), systolic_unit: [SystolicUnit](../-systolic-unit/index.html), diastolic: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), diastolic_unit: [DiastolicUnit](../-diastolic-unit/index.html), heart_rate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), heart_rate_unit: [HeartRateUnit](../-heart-rate-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [BloodPressureMood](../-blood-pressure-mood/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [diastolic](diastolic.html) | [androidJvm]<br>var [diastolic](diastolic.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [diastolic_unit](diastolic_unit.html) | [androidJvm]<br>var [diastolic_unit](diastolic_unit.html): [DiastolicUnit](../-diastolic-unit/index.html) |
| [heart_rate](heart_rate.html) | [androidJvm]<br>var [heart_rate](heart_rate.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [heart_rate_unit](heart_rate_unit.html) | [androidJvm]<br>var [heart_rate_unit](heart_rate_unit.html): [HeartRateUnit](../-heart-rate-unit/index.html) |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [BloodPressureMood](../-blood-pressure-mood/index.html)? = null |
| [systolic](systolic.html) | [androidJvm]<br>var [systolic](systolic.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [systolic_unit](systolic_unit.html) | [androidJvm]<br>var [systolic_unit](systolic_unit.html): [SystolicUnit](../-systolic-unit/index.html) |

