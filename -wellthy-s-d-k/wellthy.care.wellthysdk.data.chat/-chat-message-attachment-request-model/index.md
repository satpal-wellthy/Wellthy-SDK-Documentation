---
title: ChatMessageAttachmentRequestModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.chat](../index.html)/[ChatMessageAttachmentRequestModel](index.html)



# ChatMessageAttachmentRequestModel



[androidJvm]\
data class [ChatMessageAttachmentRequestModel](index.html)(track_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), reply_message_id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)?, attachment: [File](https://developer.android.com/reference/kotlin/java/io/File.html), attachment_type: [FileType](../-file-type/index.html), filePath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))

data class used send messages with attachments



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.chat.FileType](../-file-type/index.html) |  |
| [java.io.File](https://developer.android.com/reference/kotlin/java/io/File.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| track_id |  |
| message |  |
| reply_message_id |  |
| attachment | : File :  attachement file to be uploaded |
| attachment_type | : FileType enum (Mime type) |
| filePath | : String : Name of the file to be uploaded with extension |



## Constructors


| | |
|---|---|
| [ChatMessageAttachmentRequestModel](-chat-message-attachment-request-model.html) | [androidJvm]<br>fun [ChatMessageAttachmentRequestModel](-chat-message-attachment-request-model.html)(track_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), reply_message_id: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null, attachment: [File](https://developer.android.com/reference/kotlin/java/io/File.html), attachment_type: [FileType](../-file-type/index.html), filePath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "") |


## Properties


| Name | Summary |
|---|---|
| [attachment](attachment.html) | [androidJvm]<br>var [attachment](attachment.html): [File](https://developer.android.com/reference/kotlin/java/io/File.html) |
| [attachment_type](attachment_type.html) | [androidJvm]<br>var [attachment_type](attachment_type.html): [FileType](../-file-type/index.html) |
| [filePath](file-path.html) | [androidJvm]<br>var [filePath](file-path.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [message](message.html) | [androidJvm]<br>var [message](message.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [reply_message_id](reply_message_id.html) | [androidJvm]<br>var [reply_message_id](reply_message_id.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [track_id](track_id.html) | [androidJvm]<br>var [track_id](track_id.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

