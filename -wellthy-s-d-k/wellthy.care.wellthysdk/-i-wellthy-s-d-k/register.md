---
title: register
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)/[register](register.html)



# register



[androidJvm]\
abstract fun [register](register.html)(registerData: [RegisterDataModel](../../wellthy.care.wellthysdk.data.onboarding/-register-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;



Method to register a patient on wellthy. To be called only if the user is not registered else call login



#### Return



live data with BaseResponse



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.onboarding.RegisterDataModel](../../wellthy.care.wellthysdk.data.onboarding/-register-data-model/index.html) |  |
| [wellthy.care.wellthysdk.data.onboarding.BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html) |  |
| [wellthy.care.wellthysdk.IWellthySDK](login.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| registerData | model data class to add mandatory and optional fields |




