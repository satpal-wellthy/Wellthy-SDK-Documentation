---
title: addLabReportLog
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[addLabReportLog](add-lab-report-log.html)



# addLabReportLog



[androidJvm]\
abstract fun [addLabReportLog](add-lab-report-log.html)(type: [LogReportType](../../wellthy.care.wellthysdk.data.diary/-log-report-type/index.html), labReportModel: [LabReportLogDataModel](../../wellthy.care.wellthysdk.data.diary/-lab-report-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;



Method to add common lab report logs. Not supported lab reports will be returned with error



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
| type | : type of the lab report log that need to be added (Enum) |
| labReportModel | : LabReportLogDataModel model data class |




