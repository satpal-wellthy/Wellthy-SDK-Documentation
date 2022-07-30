---
title: wellthy.care.wellthysdk.data.magazine
---
//[WellthySDK](../../index.html)/[wellthy.care.wellthysdk.data.magazine](index.html)



# Package wellthy.care.wellthysdk.data.magazine



## Types


| Name | Summary |
|---|---|
| [ArticleByCategoryRequestDataModel](-article-by-category-request-data-model/index.html) | [androidJvm]<br>data class [ArticleByCategoryRequestDataModel](-article-by-category-request-data-model/index.html)(category_id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Data class to enter data for getArticlesByCategory function |
| [ArticleFeedbackRequestModel](-article-feedback-request-model/index.html) | [androidJvm]<br>data class [ArticleFeedbackRequestModel](-article-feedback-request-model/index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), is_helpful: [IsHelpful](-is-helpful/index.html))<br>Data class to enter data for likeArticle function |
| [ArticleRequestDataModel](-article-request-data-model/index.html) | [androidJvm]<br>data class [ArticleRequestDataModel](-article-request-data-model/index.html)(page: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), limit: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Data class to enter data for getTrendingArticleList and getLikedArticleList function |
| [IsHelpful](-is-helpful/index.html) | [androidJvm]<br>enum [IsHelpful](-is-helpful/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)&lt;[IsHelpful](-is-helpful/index.html)&gt; |
| [LikeArticleRequestModel](-like-article-request-model/index.html) | [androidJvm]<br>data class [LikeArticleRequestModel](-like-article-request-model/index.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), like_count: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Data class to enter data for likeArticle function |
| [MagazineResponse](-magazine-response/index.html) | [androidJvm]<br>data class [MagazineResponse](-magazine-response/index.html)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, data: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?, language: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, successCode: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, warnings: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[MagazineResponse.Warnings](-magazine-response/-warnings/index.html)&gt;?, sdk_version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [BaseApiResponse](../wellthy.care.wellthysdk.data.base/-base-api-response/index.html) |

