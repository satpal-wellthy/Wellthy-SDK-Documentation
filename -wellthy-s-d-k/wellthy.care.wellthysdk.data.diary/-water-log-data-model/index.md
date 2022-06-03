---
title: WaterLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[WaterLogDataModel](index.html)



# WaterLogDataModel



[androidJvm]\
data class [WaterLogDataModel](index.html)(quantity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [WaterUnit](../-water-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [WaterMoods](../-water-moods/index.html)?)

Data class to enter data for addWaterLog and updateWaterLog function



#### Return



WeightLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.WaterUnit](../-water-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.WaterMoods](../-water-moods/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| quantity | : Double, |
| unit | : WaterUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : WaterMoods? = null |



## Constructors


| | |
|---|---|
| [WaterLogDataModel](-water-log-data-model.html) | [androidJvm]<br>fun [WaterLogDataModel](-water-log-data-model.html)(quantity: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [WaterUnit](../-water-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [WaterMoods](../-water-moods/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [WaterMoods](../-water-moods/index.html)? = null |
| [quantity](quantity.html) | [androidJvm]<br>var [quantity](quantity.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [WaterUnit](../-water-unit/index.html) |

