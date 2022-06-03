---
title: MealLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[MealLogDataModel](index.html)



# MealLogDataModel



[androidJvm]\
data class [MealLogDataModel](index.html)(mealType: [MealType](../-meal-type/index.html), foodData: [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[MealFoodItem](../-meal-food-item/index.html)&gt;, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [MealsMoods](../-meals-moods/index.html)?)

Data class to enter data for addMealLog and updateMealLog function



#### Return



MealLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.MealType](../-meal-type/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.MealFoodItem](../-meal-food-item/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.MealsMoods](../-meals-moods/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| mealType | : MealType, |
| foodData | : ArrayList<MealFoodItem>, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : MealsMoods? = null |



## Constructors


| | |
|---|---|
| [MealLogDataModel](-meal-log-data-model.html) | [androidJvm]<br>fun [MealLogDataModel](-meal-log-data-model.html)(mealType: [MealType](../-meal-type/index.html), foodData: [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[MealFoodItem](../-meal-food-item/index.html)&gt;, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [MealsMoods](../-meals-moods/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [foodData](food-data.html) | [androidJvm]<br>var [foodData](food-data.html): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;[MealFoodItem](../-meal-food-item/index.html)&gt; |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [mealType](meal-type.html) | [androidJvm]<br>var [mealType](meal-type.html): [MealType](../-meal-type/index.html) |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [MealsMoods](../-meals-moods/index.html)? = null |

