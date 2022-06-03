---
title: updateActivityLog
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[updateActivityLog](update-activity-log.html)



# updateActivityLog



[androidJvm]\
abstract fun [updateActivityLog](update-activity-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), activityLogData: [ActivityLogDataModel](../../wellthy.care.wellthysdk.data.diary/-activity-log-data-model/index.html), userWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;



Method to update activity log



#### Return



live data with BaseResponse



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.ActivityLogDataModel](../../wellthy.care.wellthysdk.data.diary/-activity-log-data-model/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| logId | : id of the activity log received from server on add log |
| activityLogData | model data class to add activity details |
| userWeight | : weight of user logged in kg |




