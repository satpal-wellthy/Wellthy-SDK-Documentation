---
title: ReminderModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.profile.reminder](../index.html)/[ReminderModel](index.html)/[ReminderModel](-reminder-model.html)



# ReminderModel



[androidJvm]\
fun [ReminderModel](-reminder-model.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [ReminderType](../-reminder-type/index.html), time: &lt;ERROR CLASS&gt;&lt;[ReminderTimeModel](../-reminder-time-model/index.html)&gt;, days: &lt;ERROR CLASS&gt;&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;, start_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, end_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dosage_value: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, dosage_unit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, sub_type: [ReminderMedicineSubType](../-reminder-medicine-sub-type/index.html)? = null)



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




