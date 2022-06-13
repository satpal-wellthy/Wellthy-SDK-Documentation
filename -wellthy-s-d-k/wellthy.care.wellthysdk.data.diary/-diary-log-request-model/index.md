---
title: DiaryLogRequestModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[DiaryLogRequestModel](index.html)



# DiaryLogRequestModel



[androidJvm]\
data class [DiaryLogRequestModel](index.html)(diaryLogTypes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[DiaryLogType](../-diary-log-type/index.html)&gt;?, log_update_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?)

Data class for request params for getting diary data



#### Return



DiaryLogRequestModel object



## Parameters


androidJvm

| | |
|---|---|
| diaryLogTypes | : DiaryLogType to get, |
| log_update_date | : String, ISO 8601 Date format:  logs created/edited after this date time will be filtered |
| start_date | : String, ISO 8601 Date format: logs having log date time after this date will be filtered |
| end_date | : String, ISO 8601 Date format:  logs having log date time before this date will be filtered |
| page | : Int, page no. for pagination |
| limit | : Int, no of listing items per page |



## Constructors


| | |
|---|---|
| [DiaryLogRequestModel](-diary-log-request-model.html) | [androidJvm]<br>fun [DiaryLogRequestModel](-diary-log-request-model.html)(diaryLogTypes: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[DiaryLogType](../-diary-log-type/index.html)&gt;? = null, log_update_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [diaryLogTypes](diary-log-types.html) | [androidJvm]<br>val [diaryLogTypes](diary-log-types.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[DiaryLogType](../-diary-log-type/index.html)&gt;? = null |
| [end_date](end_date.html) | [androidJvm]<br>var [end_date](end_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [limit](limit.html) | [androidJvm]<br>var [limit](limit.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [log_update_date](log_update_date.html) | [androidJvm]<br>var [log_update_date](log_update_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [page](page.html) | [androidJvm]<br>var [page](page.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [start_date](start_date.html) | [androidJvm]<br>var [start_date](start_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |

