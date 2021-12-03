---
title: ValidateSDKResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data](../index.html)/[ValidateSDKResponse](index.html)



# ValidateSDKResponse



[androidJvm]\
data class [ValidateSDKResponse](index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [ValidateSDKResponse.Data](-data/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;) : [ApiResponseBase](../-api-response-base/index.html)



## Types


| Name | Summary |
|---|---|
| [Data](-data/index.html) | [androidJvm]<br>data class [Data](-data/index.html)(updatedAt: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, createdAt: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, clientId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, apiKey: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, whitelistedPackageNames: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, servicesData: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[ValidateSDKResponse.ServicesData](-services-data/index.html)&gt;, apiSecret: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, fixedIdSearchGsi: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, clientName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, apiLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, token: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [ServicesData](-services-data/index.html) | [androidJvm]<br>data class [ServicesData](-services-data/index.html)(service: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, baseUrl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, apiLimit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [apiStatus](../-api-response-base/api-status.html) | [androidJvm]<br>var [apiStatus](../-api-response-base/api-status.html): [ApiResponseBase.ApiStatus](../-api-response-base/-api-status/index.html) |
| [data](data.html) | [androidJvm]<br>@SerializedName(value = "data")<br>var [data](data.html): [ValidateSDKResponse.Data](-data/index.html)? |
| [language](language.html) | [androidJvm]<br>@SerializedName(value = "language")<br>var [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [message](../-api-response-base/message.html) | [androidJvm]<br>var [message](../-api-response-base/message.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.html) | [androidJvm]<br>@SerializedName(value = "status")<br>var [status](status.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [successCode](success-code.html) | [androidJvm]<br>@SerializedName(value = "successCode")<br>var [successCode](success-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [warnings](warnings.html) | [androidJvm]<br>@SerializedName(value = "warnings")<br>var [warnings](warnings.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

