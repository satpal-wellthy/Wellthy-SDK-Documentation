---
title: eGFRModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[eGFRModel](index.html)



# eGFRModel



[androidJvm]\
data class [eGFRModel](index.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [eGFRUnit](../e-g-f-r-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [ReportMoods](../-report-moods/index.html)?)

Data class to enter data for addeGFRLog function



#### Return



eGFRModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.eGFRUnit](../e-g-f-r-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.ReportMoods](../-report-moods/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| value | : Double, |
| unit | : eGFRUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : ReportMoods? = null |



## Constructors


| | |
|---|---|
| [eGFRModel](e-g-f-r-model.html) | [androidJvm]<br>fun [eGFRModel](e-g-f-r-model.html)(value: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), unit: [eGFRUnit](../e-g-f-r-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [ReportMoods](../-report-moods/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [ReportMoods](../-report-moods/index.html)? = null |
| [unit](unit.html) | [androidJvm]<br>var [unit](unit.html): [eGFRUnit](../e-g-f-r-unit/index.html) |
| [value](value.html) | [androidJvm]<br>var [value](value.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

