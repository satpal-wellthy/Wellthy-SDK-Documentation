---
title: GetChatMessagesRequestModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[GetChatMessagesRequestModel](index.html)



# GetChatMessagesRequestModel



[androidJvm]\
data class [GetChatMessagesRequestModel](index.html)(from_id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), direction: [GetMessageDirection](../-get-message-direction/index.html), count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

data class used in get Chat Messages function



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.chat.GetMessageDirection.older](../-get-message-direction/older/index.html) | to get messages having lesser id than passed id |
| [wellthy.care.wellthysdk.data.chat.GetMessageDirection.newer](../-get-message-direction/newer/index.html) | to get messages having greater id than passed id |



## Parameters


androidJvm

| | |
|---|---|
| from_id | : if from_id is 0 then most recent "count" no of messages will be fetched |
| direction | : |



## Constructors


| | |
|---|---|
| [GetChatMessagesRequestModel](-get-chat-messages-request-model.html) | [androidJvm]<br>fun [GetChatMessagesRequestModel](-get-chat-messages-request-model.html)(from_id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), direction: [GetMessageDirection](../-get-message-direction/index.html) = GetMessageDirection.newer, count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 20) |


## Properties


| Name | Summary |
|---|---|
| [count](count.html) | [androidJvm]<br>var [count](count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 20 |
| [direction](direction.html) | [androidJvm]<br>var [direction](direction.html): [GetMessageDirection](../-get-message-direction/index.html) |
| [from_id](from_id.html) | [androidJvm]<br>var [from_id](from_id.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |

