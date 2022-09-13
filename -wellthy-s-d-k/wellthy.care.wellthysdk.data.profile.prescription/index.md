---
title: wellthy.care.wellthysdk.data.profile.prescription
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.data.profile.prescription](index.html)



# Package wellthy.care.wellthysdk.data.profile.prescription



## Types


| Name | Summary |
|---|---|
| [AttachmentType](-attachment-type/index.html) | [androidJvm]<br>enum [AttachmentType](-attachment-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[AttachmentType](-attachment-type/index.html)&gt; |
| [PrescriptionAttachmentModel](-prescription-attachment-model/index.html) | [androidJvm]<br>data class [PrescriptionAttachmentModel](-prescription-attachment-model/index.html)(attachment: [File](https://developer.android.com/reference/kotlin/java/io/File.html), attachment_type: [FileType](../wellthy.care.wellthysdk.data.chat/-file-type/index.html), filePath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), attachment_id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Data class for prescription attachments |
| [PrescriptionModel](-prescription-model/index.html) | [androidJvm]<br>data class [PrescriptionModel](-prescription-model/index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), test_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), attachment: &lt;ERROR CLASS&gt;&lt;[PrescriptionAttachmentModel](-prescription-attachment-model/index.html)&gt;, attachment_type: [AttachmentType](-attachment-type/index.html))<br>Data class |
| [UpdatePrescriptionModel](-update-prescription-model/index.html) | [androidJvm]<br>data class [UpdatePrescriptionModel](-update-prescription-model/index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), test_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), prescription_ids: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;)<br>Data class for prescription update |

