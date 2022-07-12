---
title: MetaDataResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[MetaDataResponse](index.html)



# MetaDataResponse



[androidJvm]\
data class [MetaDataResponse](index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [MetaDataResponse.Data](-data/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;)



## Types


| Name | Summary |
|---|---|
| [Data](-data/index.html) | [androidJvm]<br>data class [Data](-data/index.html)(metadata: &lt;ERROR CLASS&gt;&lt;[MetaDataResponse.Metadata](-metadata/index.html)&gt;) |
| [LastMessageDetails](-last-message-details/index.html) | [androidJvm]<br>data class [LastMessageDetails](-last-message-details/index.html)(id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, createdAt: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?) |
| [Metadata](-metadata/index.html) | [androidJvm]<br>data class [Metadata](-metadata/index.html)(convId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, unreadCount: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, selfReadCursor: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, selfDeliveryCursor: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, lastSender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastMessageAt: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, readCursor: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, deliveryCursor: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, lastMessageDetails: [MetaDataResponse.LastMessageDetails](-last-message-details/index.html)?, user: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, lastSeen: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |


## Properties


| Name | Summary |
|---|---|
| [data](data.html) | [androidJvm]<br>@SerializedName(value = "data")<br>var [data](data.html): [MetaDataResponse.Data](-data/index.html)? |
| [language](language.html) | [androidJvm]<br>@SerializedName(value = "language")<br>var [language](language.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [status](status.html) | [androidJvm]<br>@SerializedName(value = "status")<br>var [status](status.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [successCode](success-code.html) | [androidJvm]<br>@SerializedName(value = "successCode")<br>var [successCode](success-code.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [warnings](warnings.html) | [androidJvm]<br>@SerializedName(value = "warnings")<br>var [warnings](warnings.html): &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |

