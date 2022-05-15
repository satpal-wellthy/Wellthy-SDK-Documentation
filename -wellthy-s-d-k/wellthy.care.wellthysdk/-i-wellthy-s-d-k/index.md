---
title: IWellthySDK
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[IWellthySDK](index.html)



# IWellthySDK



[androidJvm]\
interface [IWellthySDK](index.html)

This is interface for public methods of sdk that can be used by third party apps.



## Functions


| Name | Summary |
|---|---|
| [addActivityLog](add-activity-log.html) | [androidJvm]<br>abstract fun [addActivityLog](add-activity-log.html)(activityLogData: [ActivityLogDataModel](../../wellthy.care.wellthysdk.data.diary/-activity-log-data-model/index.html), userWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to add activity log |
| [addBloodPressureLog](add-blood-pressure-log.html) | [androidJvm]<br>abstract fun [addBloodPressureLog](add-blood-pressure-log.html)(bloodPressureLogData: [BloodPressureLogDataModel](../../wellthy.care.wellthysdk.data.diary/-blood-pressure-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to add bp log |
| [addCaregiver](add-caregiver.html) | [androidJvm]<br>abstract fun [addCaregiver](add-caregiver.html)(careGiverData: [CareGiverDataModel](../../wellthy.care.wellthysdk.data.profile.you/-care-giver-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to add caregiver data |
| [addWeightLog](add-weight-log.html) | [androidJvm]<br>abstract fun [addWeightLog](add-weight-log.html)(weightLogData: [WeightLogDataModel](../../wellthy.care.wellthysdk.data.diary/-weight-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to add weight log |
| [autoIntegrate](auto-integrate.html) | [androidJvm]<br>abstract fun [autoIntegrate](auto-integrate.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to initialize and auto integrate Wellthy SDK. To be called in onCreate |
| [deleteActivityLog](delete-activity-log.html) | [androidJvm]<br>abstract fun [deleteActivityLog](delete-activity-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to delete activity log |
| [deleteBloodPressureLog](delete-blood-pressure-log.html) | [androidJvm]<br>abstract fun [deleteBloodPressureLog](delete-blood-pressure-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to delete bp log |
| [deleteWeightLog](delete-weight-log.html) | [androidJvm]<br>abstract fun [deleteWeightLog](delete-weight-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to delete weight log |
| [login](login.html) | [androidJvm]<br>abstract fun [login](login.html)(loginData: [LoginDataModel](../../wellthy.care.wellthysdk.data.onboarding/-login-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to login an already registered patient on wellthy platform |
| [logout](logout.html) | [androidJvm]<br>abstract fun [logout](logout.html)()<br>Method to unregister Wellthy SDK. To be called on App logout |
| [register](register.html) | [androidJvm]<br>abstract fun [register](register.html)(registerData: [RegisterDataModel](../../wellthy.care.wellthysdk.data.onboarding/-register-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to register a patient on wellthy. To be called only if the user is not registered else call login |
| [updateActivityLog](update-activity-log.html) | [androidJvm]<br>abstract fun [updateActivityLog](update-activity-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), activityLogData: [ActivityLogDataModel](../../wellthy.care.wellthysdk.data.diary/-activity-log-data-model/index.html), userWeight: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to update activity log |
| [updateBloodPressureLog](update-blood-pressure-log.html) | [androidJvm]<br>abstract fun [updateBloodPressureLog](update-blood-pressure-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), bloodPressureLogData: [BloodPressureLogDataModel](../../wellthy.care.wellthysdk.data.diary/-blood-pressure-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to update bp log |
| [updateCaregiver](update-caregiver.html) | [androidJvm]<br>abstract fun [updateCaregiver](update-caregiver.html)(careGiverData: [CareGiverDataModel](../../wellthy.care.wellthysdk.data.profile.you/-care-giver-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to update caregiver data |
| [updateHealthDetails](update-health-details.html) | [androidJvm]<br>abstract fun [updateHealthDetails](update-health-details.html)(healthDetaisData: [HealthDetailsDataModel](../../wellthy.care.wellthysdk.data.profile.you/-health-details-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to set/update profile health details variables |
| [updateProfile](update-profile.html) | [androidJvm]<br>abstract fun [updateProfile](update-profile.html)(profileData: [ProfileDataModel](../../wellthy.care.wellthysdk.data.profile.you/-profile-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to set/update profile variables |
| [updateWeightLog](update-weight-log.html) | [androidJvm]<br>abstract fun [updateWeightLog](update-weight-log.html)(logId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), weightLogData: [WeightLogDataModel](../../wellthy.care.wellthysdk.data.diary/-weight-log-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to update weight log |


## Inheritors


| Name |
|---|
| [WellthySDK](../-wellthy-s-d-k/index.html) |

