---
title: updateLabReportLog
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[WellthySDK](index.html)/[updateLabReportLog](update-lab-report-log.html)



# updateLabReportLog



[androidJvm]\
open override fun [updateLabReportLog](update-lab-report-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), type: [LogReportType](../../wellthy.care.wellthysdk.data.diary/-log-report-type/index.html), labReportModel: [LabReportLogDataModel](../../wellthy.care.wellthysdk.data.diary/-lab-report-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;



Method to update common lab report logs. Not supported lab reports will be returned with error



#### Return



live data with BaseResponse



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.LabReportLogDataModel](../../wellthy.care.wellthysdk.data.diary/-lab-report-log-data-model/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| logId | : id of the log to be updated |
| type | : type of the lab report log that need to be updated (Enum) |
| labReportModel | : LabReportLogDataModel model data class |




