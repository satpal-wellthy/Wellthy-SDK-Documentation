---
title: wellthy.care.wellthysdk.data.profile.reminder
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.data.profile.reminder](index.html)



# Package wellthy.care.wellthysdk.data.profile.reminder



## Types


| Name | Summary |
|---|---|
| [ReminderMedicineSubType](-reminder-medicine-sub-type/index.html) | [androidJvm]<br>enum [ReminderMedicineSubType](-reminder-medicine-sub-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ReminderMedicineSubType](-reminder-medicine-sub-type/index.html)&gt; |
| [ReminderModel](-reminder-model/index.html) | [androidJvm]<br>data class [ReminderModel](-reminder-model/index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [ReminderType](-reminder-type/index.html), time: &lt;ERROR CLASS&gt;&lt;[ReminderTimeModel](-reminder-time-model/index.html)&gt;, days: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dosage_value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dosage_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, sub_type: [ReminderMedicineSubType](-reminder-medicine-sub-type/index.html)?)<br>Data class to enter data for addReminder function |
| [ReminderTimeModel](-reminder-time-model/index.html) | [androidJvm]<br>data class [ReminderTimeModel](-reminder-time-model/index.html)(e: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), t: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), i: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>Time params of the reminder. "i" is track id, "e" is enabled flag boolean and "t" is time of the event. |
| [ReminderType](-reminder-type/index.html) | [androidJvm]<br>enum [ReminderType](-reminder-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[ReminderType](-reminder-type/index.html)&gt; |

