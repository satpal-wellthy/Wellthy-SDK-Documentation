---
title: Companion
---
//[WellthySDK](../../../../index.html)/[wellthy.care.wellthysdk.utils.chat](../../index.html)/[ChatManager](../index.html)/[Companion](index.html)



# Companion



[androidJvm]\
object [Companion](index.html) : AWSIotMqttNewMessageCallback



## Functions


| Name | Summary |
|---|---|
| [connectChat](connect-chat.html) | [androidJvm]<br>fun [connectChat](connect-chat.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), _chatLiveData: [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;) |
| [disconnectChat](disconnect-chat.html) | [androidJvm]<br>fun [disconnectChat](disconnect-chat.html)() |
| [disconnectChatOnAppGoingInBackground](disconnect-chat-on-app-going-in-background.html) | [androidJvm]<br>fun [disconnectChatOnAppGoingInBackground](disconnect-chat-on-app-going-in-background.html)() |
| [initChatStatusListener](init-chat-status-listener.html) | [androidJvm]<br>fun [initChatStatusListener](init-chat-status-listener.html)(chatStatusListener: [ChatStatusListener](../../-chat-status-listener/index.html)) |
| [logEventMqtt](log-event-mqtt.html) | [androidJvm]<br>fun [logEventMqtt](log-event-mqtt.html)(logEvent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>fun [logEventMqtt](log-event-mqtt.html)(logEvent: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), throwable: [Throwable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)) |
| [mqtttopicBuilder](mqtttopic-builder.html) | [androidJvm]<br>fun [mqtttopicBuilder](mqtttopic-builder.html)(userId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [onMessageArrived](on-message-arrived.html) | [androidJvm]<br>open override fun [onMessageArrived](on-message-arrived.html)(topic: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, data: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)?) |
| [reConnectChat](re-connect-chat.html) | [androidJvm]<br>fun [reConnectChat](re-connect-chat.html)() |
| [sendStatusCursor](send-status-cursor.html) | [androidJvm]<br>fun [sendStatusCursor](send-status-cursor.html)(isOnline: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), conversationId: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L) |
| [sendTyping](send-typing.html) | [androidJvm]<br>fun [sendTyping](send-typing.html)() |


## Properties


| Name | Summary |
|---|---|
| [chatLiveData](chat-live-data.html) | [androidJvm]<br>var [chatLiveData](chat-live-data.html): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;? = null |
| [isChatConnected](is-chat-connected.html) | [androidJvm]<br>var [isChatConnected](is-chat-connected.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [isChatInitializing](is-chat-initializing.html) | [androidJvm]<br>var [isChatInitializing](is-chat-initializing.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [mqttManager](mqtt-manager.html) | [androidJvm]<br>var [mqttManager](mqtt-manager.html): AWSIotMqttManager? = null |

