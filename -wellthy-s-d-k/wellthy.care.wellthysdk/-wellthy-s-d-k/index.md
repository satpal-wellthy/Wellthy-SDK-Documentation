---
title: WellthySDK
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk](../index.html)/[WellthySDK](index.html)



# WellthySDK



[androidJvm]\
object [WellthySDK](index.html) : [IWellthySDK](../-i-wellthy-s-d-k/index.html)



## Functions


| Name | Summary |
|---|---|
| [addCaregiver](add-caregiver.html) | [androidJvm]<br>open override fun [addCaregiver](add-caregiver.html)(careGiverData: [CareGiverDataModel](../../wellthy.care.wellthysdk.data.profile.you/-care-giver-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to add caregiver data |
| [autoIntegrate](auto-integrate.html) | [androidJvm]<br>open override fun [autoIntegrate](auto-integrate.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to initialize and auto integrate Wellthy SDK. To be called in onCreate |
| [deleteCaregiver](delete-caregiver.html) | [androidJvm]<br>open override fun [deleteCaregiver](delete-caregiver.html)(careGiverData: [CareGiverDataModel](../../wellthy.care.wellthysdk.data.profile.you/-care-giver-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to delete caregiver data |
| [login](login.html) | [androidJvm]<br>open override fun [login](login.html)(loginData: [LoginDataModel](../../wellthy.care.wellthysdk.data.onboarding/-login-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to login an already registered patient on wellthy platform |
| [logout](logout.html) | [androidJvm]<br>open override fun [logout](logout.html)()<br>Method to unregister Wellthy SDK. To be called on App logout |
| [register](register.html) | [androidJvm]<br>open override fun [register](register.html)(registerData: [RegisterDataModel](../../wellthy.care.wellthysdk.data.onboarding/-register-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to register a patient on wellthy. To be called only if the user is not registered else call login |
| [updateCaregiver](update-caregiver.html) | [androidJvm]<br>open override fun [updateCaregiver](update-caregiver.html)(careGiverData: [CareGiverDataModel](../../wellthy.care.wellthysdk.data.profile.you/-care-giver-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to update caregiver data |
| [updateHealthDetails](update-health-details.html) | [androidJvm]<br>open override fun [updateHealthDetails](update-health-details.html)(healthDetaisData: [HealthDetailsDataModel](../../wellthy.care.wellthysdk.data.profile.you/-health-details-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to set/update profile health details variables |
| [updateProfile](update-profile.html) | [androidJvm]<br>open override fun [updateProfile](update-profile.html)(profileData: [ProfileDataModel](../../wellthy.care.wellthysdk.data.profile.you/-profile-data-model/index.html)): [MutableLiveData](https://developer.android.com/reference/kotlin/androidx/lifecycle/MutableLiveData.html)&lt;[BaseResponse](../../wellthy.care.wellthysdk.data.onboarding/-base-response/index.html)&gt;<br>Method to set/update profile variables |

