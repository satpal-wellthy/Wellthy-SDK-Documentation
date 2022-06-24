---
title: GoogleFitSyncingManager
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.utils](../index.html)/[GoogleFitSyncingManager](index.html)



# GoogleFitSyncingManager



[androidJvm]\
class [GoogleFitSyncingManager](index.html)



## Constructors


| | |
|---|---|
| [GoogleFitSyncingManager](-google-fit-syncing-manager.html) | [androidJvm]<br>fun [GoogleFitSyncingManager](-google-fit-syncing-manager.html)() |
| [GoogleFitSyncingManager](-google-fit-syncing-manager.html) | [androidJvm]<br>fun [GoogleFitSyncingManager](-google-fit-syncing-manager.html)(callbacks: [IGoogleFitSyncingCallbacks](../-i-google-fit-syncing-callbacks/index.html)?, context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |
| [GoogleFitSyncingManager](-google-fit-syncing-manager.html) | [androidJvm]<br>fun [GoogleFitSyncingManager](-google-fit-syncing-manager.html)(context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)) |


## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [androidJvm]<br>object [Companion](-companion/index.html) |
| [SyncingDataType](-syncing-data-type/index.html) | [androidJvm]<br>enum [SyncingDataType](-syncing-data-type/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[GoogleFitSyncingManager.SyncingDataType](-syncing-data-type/index.html)&gt; |
| [SyncingRequestCustom](-syncing-request-custom/index.html) | [androidJvm]<br>class [SyncingRequestCustom](-syncing-request-custom/index.html) |


## Functions


| Name | Summary |
|---|---|
| [getEndTimeString](get-end-time-string.html) | [androidJvm]<br>fun DataPoint.[getEndTimeString](get-end-time-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getStartTimeString](get-start-time-string.html) | [androidJvm]<br>fun DataPoint.[getStartTimeString](get-start-time-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [onGoogleFitDataReceived](on-google-fit-data-received.html) | [androidJvm]<br>fun [onGoogleFitDataReceived](on-google-fit-data-received.html)(data: [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[GoogleFitDataModel](../../wellthy.care.wellthysdk.data.diary/-google-fit-data-model/index.html)&gt;&gt;) |
| [sync](sync.html) | [androidJvm]<br>fun [sync](sync.html)() |


## Properties


| Name | Summary |
|---|---|
| [arrSyncingRequestCustom](arr-syncing-request-custom.html) | [androidJvm]<br>var [arrSyncingRequestCustom](arr-syncing-request-custom.html): [ArrayList](https://developer.android.com/reference/kotlin/java/util/ArrayList.html)&lt;[GoogleFitSyncingManager.SyncingRequestCustom](-syncing-request-custom/index.html)&gt;? = null |
| [callbacks](callbacks.html) | [androidJvm]<br>var [callbacks](callbacks.html): [IGoogleFitSyncingCallbacks](../-i-google-fit-syncing-callbacks/index.html)? = null |
| [context](context.html) | [androidJvm]<br>var [context](context.html): [Context](https://developer.android.com/reference/kotlin/android/content/Context.html)? = null |
| [googleFitUnit](google-fit-unit.html) | [androidJvm]<br>var [googleFitUnit](google-fit-unit.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [isSyncingInProgress](is-syncing-in-progress.html) | [androidJvm]<br>var [isSyncingInProgress](is-syncing-in-progress.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [mapDataDayWise](map-data-day-wise.html) | [androidJvm]<br>val [mapDataDayWise](map-data-day-wise.html): &lt;ERROR CLASS&gt; |
| [todaysStepCount](todays-step-count.html) | [androidJvm]<br>var [todaysStepCount](todays-step-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

