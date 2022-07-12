---
title: MessageReceivedResponse
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[MessageReceivedResponse](index.html)



# MessageReceivedResponse



[androidJvm]\
data class [MessageReceivedResponse](index.html)(conversationId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, sender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, participants: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, trackId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mimeType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, replyTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, sendType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, attachment: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, senderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?)

Data class which gives the response for received message



## Constructors


| | |
|---|---|
| [MessageReceivedResponse](-message-received-response.html) | [androidJvm]<br>fun [MessageReceivedResponse](-message-received-response.html)(conversationId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null, sender: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, clientId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, participants: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; = arrayListOf(), body: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, trackId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mimeType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, replyTo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, sendType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, attachment: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, senderName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null, timestamp: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null, userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [attachment](attachment.html) | [androidJvm]<br>@SerializedName(value = "attachment")<br>var [attachment](attachment.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [body](body.html) | [androidJvm]<br>@SerializedName(value = "body")<br>var [body](body.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [clientId](client-id.html) | [androidJvm]<br>@SerializedName(value = "clientId")<br>var [clientId](client-id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [conversationId](conversation-id.html) | [androidJvm]<br>@SerializedName(value = "conversationId")<br>var [conversationId](conversation-id.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [id](id.html) | [androidJvm]<br>@SerializedName(value = "id")<br>var [id](id.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [mimeType](mime-type.html) | [androidJvm]<br>@SerializedName(value = "mimeType")<br>var [mimeType](mime-type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [participants](participants.html) | [androidJvm]<br>@SerializedName(value = "participants")<br>var [participants](participants.html): &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [replyTo](reply-to.html) | [androidJvm]<br>@SerializedName(value = "replyTo")<br>var [replyTo](reply-to.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [sender](sender.html) | [androidJvm]<br>@SerializedName(value = "sender")<br>var [sender](sender.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [senderName](sender-name.html) | [androidJvm]<br>@SerializedName(value = "senderName")<br>var [senderName](sender-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [sendType](send-type.html) | [androidJvm]<br>@SerializedName(value = "sendType")<br>var [sendType](send-type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [timestamp](timestamp.html) | [androidJvm]<br>@SerializedName(value = "timestamp")<br>var [timestamp](timestamp.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [trackId](track-id.html) | [androidJvm]<br>@SerializedName(value = "trackId")<br>var [trackId](track-id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [type](type.html) | [androidJvm]<br>@SerializedName(value = "type")<br>var [type](type.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [userId](user-id.html) | [androidJvm]<br>@SerializedName(value = "userId")<br>var [userId](user-id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |

