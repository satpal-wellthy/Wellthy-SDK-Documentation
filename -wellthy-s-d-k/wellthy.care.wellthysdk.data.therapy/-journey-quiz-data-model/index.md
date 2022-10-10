---
title: JourneyQuizDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.therapy](../index.html)/[JourneyQuizDataModel](index.html)



# JourneyQuizDataModel



[androidJvm]\
data class [JourneyQuizDataModel](index.html)(level_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), module_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), chapter_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), quiz_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), start_time: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), end_time: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), retry_number: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mark_chapter_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_module_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_level_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_therapy_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modules: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

Data class to enter data for saveQuizProgress function Note that "modules" will have comma separated values



#### Return



Response object



## See also


androidJvm

| | |
|---|---|
| saveQuizProgress |  |



## Constructors


| | |
|---|---|
| [JourneyQuizDataModel](-journey-quiz-data-model.html) | [androidJvm]<br>fun [JourneyQuizDataModel](-journey-quiz-data-model.html)(level_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), module_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), chapter_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), quiz_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), start_time: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), end_time: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), retry_number: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1, mark_chapter_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_module_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_level_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), mark_therapy_complete: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), modules: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [chapter_id](chapter_id.html) | [androidJvm]<br>var [chapter_id](chapter_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [end_time](end_time.html) | [androidJvm]<br>var [end_time](end_time.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [level_id](level_id.html) | [androidJvm]<br>var [level_id](level_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mark_chapter_complete](mark_chapter_complete.html) | [androidJvm]<br>var [mark_chapter_complete](mark_chapter_complete.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mark_level_complete](mark_level_complete.html) | [androidJvm]<br>var [mark_level_complete](mark_level_complete.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mark_module_complete](mark_module_complete.html) | [androidJvm]<br>var [mark_module_complete](mark_module_complete.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mark_therapy_complete](mark_therapy_complete.html) | [androidJvm]<br>var [mark_therapy_complete](mark_therapy_complete.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [module_id](module_id.html) | [androidJvm]<br>var [module_id](module_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [modules](modules.html) | [androidJvm]<br>var [modules](modules.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [quiz_id](quiz_id.html) | [androidJvm]<br>var [quiz_id](quiz_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [retry_number](retry_number.html) | [androidJvm]<br>var [retry_number](retry_number.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [start_time](start_time.html) | [androidJvm]<br>var [start_time](start_time.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

