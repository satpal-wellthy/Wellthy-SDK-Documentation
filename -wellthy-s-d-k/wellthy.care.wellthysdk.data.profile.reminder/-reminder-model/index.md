---
title: ReminderModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.profile.reminder](../index.html)/[ReminderModel](index.html)



# ReminderModel



[androidJvm]\
data class [ReminderModel](index.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [ReminderType](../-reminder-type/index.html), time: &lt;ERROR CLASS&gt;&lt;[ReminderTimeModel](../-reminder-time-model/index.html)&gt;, days: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dosage_value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, dosage_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, sub_type: [ReminderMedicineSubType](../-reminder-medicine-sub-type/index.html)?)

Data class to enter data for addReminder function



#### Return



ReminderModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.profile.reminder.ReminderTimeModel](../-reminder-time-model/index.html) |  |
| [wellthy.care.wellthysdk.data.profile.reminder.ReminderMedicineSubType](../-reminder-medicine-sub-type/index.html) |  |
| [wellthy.care.wellthysdk.data.profile.reminder.ReminderType](../-reminder-type/index.html) |  |
| addReminder |  |



## Parameters


androidJvm

| | |
|---|---|
| name | : String : Title of the reminder |
| type | : ReminderType : Type of reminder. Enums |
| time | : ArrayList<ReminderTimeModel> : Time params of the reminder. "i" is track id, "e" is enabled flag boolean and "t" is time of the event. |
| days | : ArrayList<String> : Days array. 1= Monday, 7 = Saturday. 1,2,3,4,5,6,7 |
| start_date | : String? : Start date |
| end_date | : String? : End date |
| dosage_value | : String? : this should be comma separated string. Dosage value for medicine |
| dosage_unit | : String? : Unit of dosage |
| sub_type | : ReminderMedicineSubType? : Type of medicine. Enums |



## Constructors


| | |
|---|---|
| [ReminderModel](-reminder-model.html) | [androidJvm]<br>fun [ReminderModel](-reminder-model.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [ReminderType](../-reminder-type/index.html), time: &lt;ERROR CLASS&gt;&lt;[ReminderTimeModel](../-reminder-time-model/index.html)&gt;, days: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dosage_value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dosage_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, sub_type: [ReminderMedicineSubType](../-reminder-medicine-sub-type/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [days](days.html) | [androidJvm]<br>var [days](days.html): &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt; |
| [dosage_unit](dosage_unit.html) | [androidJvm]<br>var [dosage_unit](dosage_unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [dosage_value](dosage_value.html) | [androidJvm]<br>var [dosage_value](dosage_value.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [end_date](end_date.html) | [androidJvm]<br>var [end_date](end_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [name](name.html) | [androidJvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [start_date](start_date.html) | [androidJvm]<br>var [start_date](start_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [sub_type](sub_type.html) | [androidJvm]<br>var [sub_type](sub_type.html): [ReminderMedicineSubType](../-reminder-medicine-sub-type/index.html)? = null |
| [time](time.html) | [androidJvm]<br>var [time](time.html): &lt;ERROR CLASS&gt;&lt;[ReminderTimeModel](../-reminder-time-model/index.html)&gt; |
| [type](type.html) | [androidJvm]<br>var [type](type.html): [ReminderType](../-reminder-type/index.html) |

