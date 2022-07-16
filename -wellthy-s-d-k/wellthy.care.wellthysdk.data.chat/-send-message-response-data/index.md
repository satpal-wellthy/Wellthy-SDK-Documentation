---
title: SendMessageResponseData
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[SendMessageResponseData](index.html)



# SendMessageResponseData



[androidJvm]\
data class [SendMessageResponseData](index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [SendMessageResponseData.Data](-data/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;)



## Types


| Name | Summary |
|---|---|
| [Data](-data/index.html) | [androidJvm]<br>data class [Data](-data/index.html)(conversationId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, sender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, trackId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), participants: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mimeType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, replyTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, sendType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [androidJvm]<br>@SerializedName(value = "data")<br>var [data](data.html): [SendMessageResponseData.Data](-data/index.html)? |
| [language](language.html) | [androidJvm]<br>@SerializedName(value = "language")<br>var [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [status](status.html) | [androidJvm]<br>@SerializedName(value = "status")<br>var [status](status.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [successCode](success-code.html) | [androidJvm]<br>@SerializedName(value = "successCode")<br>var [successCode](success-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [warnings](warnings.html) | [androidJvm]<br>@SerializedName(value = "warnings")<br>var [warnings](warnings.html): &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

