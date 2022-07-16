---
title: ElectrolytesModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[ElectrolytesModel](index.html)



# ElectrolytesModel



[androidJvm]\
data class [ElectrolytesModel](index.html)(sodium: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sodium_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), potassium: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), potassium_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), chloride: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), chloride_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), bicarbonate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), bicarbonate_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [ReportMood](../-report-mood/index.html)?)

Data class to enter data for addElectrolytesLog function



#### Return



ElectrolytesModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.ElectrolytesUnit](../-electrolytes-unit/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.ReportMood](../-report-mood/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| sodium | : Double, |
| sodium_unit | : ElectrolytesUnit, |
| potassium | : Double, |
| potassium_unit | : ElectrolytesUnit, |
| chloride | : Double, |
| chloride_unit | : ElectrolytesUnit, |
| bicarbonate | : Double, |
| bicarbonate_unit | : ElectrolytesUnit, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : ReportMood? = null |



## Constructors


| | |
|---|---|
| [ElectrolytesModel](-electrolytes-model.html) | [androidJvm]<br>fun [ElectrolytesModel](-electrolytes-model.html)(sodium: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), sodium_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), potassium: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), potassium_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), chloride: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), chloride_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), bicarbonate: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), bicarbonate_unit: [ElectrolytesUnit](../-electrolytes-unit/index.html), log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [ReportMood](../-report-mood/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [bicarbonate](bicarbonate.html) | [androidJvm]<br>var [bicarbonate](bicarbonate.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [bicarbonate_unit](bicarbonate_unit.html) | [androidJvm]<br>var [bicarbonate_unit](bicarbonate_unit.html): [ElectrolytesUnit](../-electrolytes-unit/index.html) |
| [chloride](chloride.html) | [androidJvm]<br>var [chloride](chloride.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [chloride_unit](chloride_unit.html) | [androidJvm]<br>var [chloride_unit](chloride_unit.html): [ElectrolytesUnit](../-electrolytes-unit/index.html) |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [ReportMood](../-report-mood/index.html)? = null |
| [potassium](potassium.html) | [androidJvm]<br>var [potassium](potassium.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [potassium_unit](potassium_unit.html) | [androidJvm]<br>var [potassium_unit](potassium_unit.html): [ElectrolytesUnit](../-electrolytes-unit/index.html) |
| [sodium](sodium.html) | [androidJvm]<br>var [sodium](sodium.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [sodium_unit](sodium_unit.html) | [androidJvm]<br>var [sodium_unit](sodium_unit.html): [ElectrolytesUnit](../-electrolytes-unit/index.html) |

