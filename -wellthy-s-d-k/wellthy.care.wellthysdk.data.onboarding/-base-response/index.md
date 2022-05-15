---
title: BaseResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.onboarding](../index.html)/[BaseResponse](index.html)



# BaseResponse



[androidJvm]\
data class [BaseResponse](index.html)(code: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, response: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, error: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

Base response for all callbacks



## Parameters


androidJvm

| | |
|---|---|
| code | contains Status code |
| response | object containing data from API : nullable |
| error | error message in case of error response : nullable |



## Constructors


| | |
|---|---|
| [BaseResponse](-base-response.html) | [androidJvm]<br>fun [BaseResponse](-base-response.html)(code: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = BaseApiResponse.ApiStatus.None.defaultCode, response: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? = null, error: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [code](code.html) | [androidJvm]<br>var [code](code.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [error](error.html) | [androidJvm]<br>var [error](error.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [response](response.html) | [androidJvm]<br>var [response](response.html): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? = null |

