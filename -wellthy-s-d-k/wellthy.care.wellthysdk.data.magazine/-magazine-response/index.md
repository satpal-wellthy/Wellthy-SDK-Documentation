---
title: MagazineResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.magazine](../index.html)/[MagazineResponse](index.html)



# MagazineResponse



[androidJvm]\
data class [MagazineResponse](index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[MagazineResponse.Warnings](-warnings/index.html)&gt;?, sdk_version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [BaseApiResponse](../../wellthy.care.wellthysdk.data.base/-base-api-response/index.html)



## Types


| Name | Summary |
|---|---|
| [Warnings](-warnings/index.html) | [androidJvm]<br>data class [Warnings](-warnings/index.html)(warningCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), warningMessage: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [androidJvm]<br>@SerializedName(value = "data")<br>var [data](data.html): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)? = null |
| [language](language.html) | [androidJvm]<br>@SerializedName(value = "language")<br>var [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [sdk_version](sdk_version.html) | [androidJvm]<br>@SerializedName(value = "sdk_version")<br>var [sdk_version](sdk_version.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [status](status.html) | [androidJvm]<br>@SerializedName(value = "status")<br>var [status](status.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [successCode](success-code.html) | [androidJvm]<br>@SerializedName(value = "successCode")<br>var [successCode](success-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [warnings](warnings.html) | [androidJvm]<br>@SerializedName(value = "warnings")<br>var [warnings](warnings.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[MagazineResponse.Warnings](-warnings/index.html)&gt;? = null |

