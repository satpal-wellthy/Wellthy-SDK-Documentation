---
title: ApiInterface
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.api](../index.html)/[ApiInterface](index.html)



# ApiInterface



[androidJvm]\
interface [ApiInterface](index.html)



## Functions


| Name | Summary |
|---|---|
| [diary](diary.html) | [androidJvm]<br>@FormUrlEncoded<br>@POST<br>abstract suspend fun [diary](diary.html)(@Urlurl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Header(value = "x-access-token")accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @FieldMaprequestMap: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): Response&lt;[DiaryLogResponse](../../wellthy.care.wellthysdk.data.diary/-diary-log-response/index.html)?&gt; |
| [inValidateSDK](in-validate-s-d-k.html) | [androidJvm]<br>@POST(value = "/auth")<br>abstract suspend fun [inValidateSDK](in-validate-s-d-k.html)(@HeaderMaprequestMap: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): Response&lt;[ValidateSDKResponse](../../wellthy.care.wellthysdk.data.onboarding/-validate-s-d-k-response/index.html)?&gt;<br>SDK Authorisation api |
| [register](register.html) | [androidJvm]<br>@FormUrlEncoded<br>@POST<br>abstract suspend fun [register](register.html)(@Urlurl: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @Header(value = "x-access-token")accessToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), @FieldMaprequestMap: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): Response&lt;[RegisterResponse](../../wellthy.care.wellthysdk.data.onboarding/-register-response/index.html)?&gt; |

