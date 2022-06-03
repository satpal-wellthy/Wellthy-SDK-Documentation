---
title: SymptomsLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[SymptomsLogDataModel](index.html)



# SymptomsLogDataModel



[androidJvm]\
data class [SymptomsLogDataModel](index.html)(log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, symptoms_answers: [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[SymptomAnswers](../-symptom-answers/index.html)&gt;)

Data class to enter data for addSymptomsLog and updateSymptomsLog function



#### Return



SymptomsLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.SymptomAnswers](../-symptom-answers/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.SymptomValue](../-symptom-value/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| symptoms_answers | : ArrayList<SymptomAnswers> |



## Constructors


| | |
|---|---|
| [SymptomsLogDataModel](-symptoms-log-data-model.html) | [androidJvm]<br>fun [SymptomsLogDataModel](-symptoms-log-data-model.html)(log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, symptoms_answers: [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[SymptomAnswers](../-symptom-answers/index.html)&gt;) |


## Properties


| Name | Summary |
|---|---|
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [symptoms_answers](symptoms_answers.html) | [androidJvm]<br>var [symptoms_answers](symptoms_answers.html): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[SymptomAnswers](../-symptom-answers/index.html)&gt; |

