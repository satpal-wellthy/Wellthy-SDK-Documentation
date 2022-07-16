---
title: MealLogDataModel
---
//[WellthySDK](../../../index.html)/[wellthy.care.wellthysdk.data.diary](../index.html)/[MealLogDataModel](index.html)



# MealLogDataModel



[androidJvm]\
data class [MealLogDataModel](index.html)(meal_type: [MealType](../-meal-type/index.html), food_data: &lt;ERROR CLASS&gt;&lt;[MealFoodItem](../-meal-food-item/index.html)&gt;, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, mood: [MealsMood](../-meals-mood/index.html)?)

Data class to enter data for addMealLog and updateMealLog function



#### Return



MealLogDataModel object



## See also


androidJvm

| | |
|---|---|
| [wellthy.care.wellthysdk.data.diary.MealType](../-meal-type/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.MealFoodItem](../-meal-food-item/index.html) |  |
| [wellthy.care.wellthysdk.data.diary.MealsMood](../-meals-mood/index.html) |  |



## Parameters


androidJvm

| | |
|---|---|
| meal_type | : MealType, |
| food_data | : ArrayList<MealFoodItem>, |
| log_date | : String, // ISO 8601 Date format |
| latitude | : String? = null, |
| longitude | : String? = null, |
| location_name | : String? = null, |
| mood | : MealsMood? = null |



## Constructors


| | |
|---|---|
| [MealLogDataModel](-meal-log-data-model.html) | [androidJvm]<br>fun [MealLogDataModel](-meal-log-data-model.html)(meal_type: [MealType](../-meal-type/index.html), food_data: &lt;ERROR CLASS&gt;&lt;[MealFoodItem](../-meal-food-item/index.html)&gt;, log_date: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), latitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, longitude: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, location_name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, mood: [MealsMood](../-meals-mood/index.html)? = null) |


## Properties


| Name | Summary |
|---|---|
| [food_data](food_data.html) | [androidJvm]<br>var [food_data](food_data.html): &lt;ERROR CLASS&gt;&lt;[MealFoodItem](../-meal-food-item/index.html)&gt; |
| [latitude](latitude.html) | [androidJvm]<br>var [latitude](latitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [location_name](location_name.html) | [androidJvm]<br>var [location_name](location_name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [log_date](log_date.html) | [androidJvm]<br>var [log_date](log_date.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [longitude](longitude.html) | [androidJvm]<br>var [longitude](longitude.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [meal_type](meal_type.html) | [androidJvm]<br>var [meal_type](meal_type.html): [MealType](../-meal-type/index.html) |
| [mood](mood.html) | [androidJvm]<br>var [mood](mood.html): [MealsMood](../-meals-mood/index.html)? = null |

