---
title: updateBloodPressureLog
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[updateBloodPressureLog](update-blood-pressure-log.html)



# updateBloodPressureLog



[androidJvm]\
abstract fun [updateBloodPressureLog](update-blood-pressure-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bloodPressureLogData: [BloodPressureLogDataModel](../../wellthy.care.wellthysdk.data.diary/-blood-pressure-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;



Method to update bp log



#### Return



live data with BaseResponse



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.BloodPressureLogDataModel](../../wellthy.care.wellthysdk.data.diary/-blood-pressure-log-data-model/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| logId | : id of the bp log received from server on add log |
| bloodPressureLogData | model data class to add bp details |




