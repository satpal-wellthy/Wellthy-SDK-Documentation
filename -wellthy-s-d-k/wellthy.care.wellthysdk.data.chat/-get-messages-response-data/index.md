---
title: GetMessagesResponseData
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[GetMessagesResponseData](index.html)



# GetMessagesResponseData



[androidJvm]\
data class [GetMessagesResponseData](index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [GetMessagesResponseData.Data](-data/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;)



## Types


| Name | Summary |
|---|---|
| [Attachment](-attachment/index.html) | [androidJvm]<br>data class [Attachment](-attachment/index.html)(link: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, length: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, size: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, additionalData: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [Data](-data/index.html) | [androidJvm]<br>data class [Data](-data/index.html)(messages: &lt;ERROR CLASS&gt;&lt;[GetMessagesResponseData.Messages](-messages/index.html)&gt;) |
| [Messages](-messages/index.html) | [androidJvm]<br>data class [Messages](-messages/index.html)(attachment: [GetMessagesResponseData.Attachment](-attachment/index.html)?, id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, trackId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, sender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mimeType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, replyTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, isDeleted: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, isUserLiked: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, isHcLiked: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, updatedAt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [androidJvm]<br>@SerializedName(value = "data")<br>var [data](data.html): [GetMessagesResponseData.Data](-data/index.html)? |
| [language](language.html) | [androidJvm]<br>@SerializedName(value = "language")<br>var [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [status](status.html) | [androidJvm]<br>@SerializedName(value = "status")<br>var [status](status.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [successCode](success-code.html) | [androidJvm]<br>@SerializedName(value = "successCode")<br>var [successCode](success-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [warnings](warnings.html) | [androidJvm]<br>@SerializedName(value = "warnings")<br>var [warnings](warnings.html): &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

