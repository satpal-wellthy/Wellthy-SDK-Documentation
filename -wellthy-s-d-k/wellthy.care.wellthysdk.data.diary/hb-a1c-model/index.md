---
title: hbA1cModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[hbA1cModel](index.html)



# hbA1cModel



[androidJvm]\
data class [hbA1cModel](index.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [hbA1cUnit](../hb-a1c-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [ReportMood](../-report-mood/index.html)?)

Data class to enter data for addHbA1cLog  function



#### Return



hbA1cModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.hbA1cUnit](../hb-a1c-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.ReportMood](../-report-mood/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| value | : Double, |
| unit | : hbA1cUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : ReportMood? = null |



## Constructors


| | |
|---|---|
| [hbA1cModel](hb-a1c-model.html) | [androidJvm]<br>fun [hbA1cModel](hb-a1c-model.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [hbA1cUnit](../hb-a1c-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [ReportMood](../-report-mood/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [ReportMood](../-report-mood/index.html)? = null |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [hbA1cUnit](../hb-a1c-unit/index.html) |
| [value](value.html) | [androidJvm]<br>var [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

