# Recipes_Calories_Analysis
**Name(s)**: Yujin Lee
**Website Link**: https://yul243.github.io/Recipes_Calories_Steps/
---
## Step 1: Introduction
There are countless kinds of food worldwide; accordingly, there are many different recipes. There are also different versions of recipes for one food, which depend on the combination of each cooking process and ingredients. In this project, we explore the presence or absence of calorie changes based on the number of steps in a recipe. The research is expected to contribute to understanding the relationship between the complexity of the cooking process and health.

### Introduction to the Datasets
The project will use two datasets, both from food.com. The first is `RAW_recipes.csv`, a dataset of cooking recipes from 2008 to 2018. It consists of 83782 rows and 12 columns. See the table below for a detailed description.

|Column	                 |Description|
|---                     |---        |
|`'name'	`            |Recipe name|
|`'id'`	                 |Recipe ID|
|`'minutes'`	         |Minutes to prepare recipe|
|`'contributor_id'`	     |User ID who submitted this recipe|
|`'submitted'`	            | Date recipe was submitted|
|`'tags'`	              |Food.com tags for recipe|
|`'nutrition'`	          |Nutrition information in the form [calories (#), total fat (PDV), sugar (PDV), sodium (PDV), protein    (PDV), saturated fat (PDV), carbohydrates (PDV)]; PDV stands for “percentage of daily value”|
|`'n_steps'`	          |Number of steps in recipe|
|`'steps'`	              |Text for recipe steps, in order|
|`'description'`	     | User-provided description|

The second data set is `RAW_interactions.csv`, which evaluates and reviews recipes contained in `RAW_recipes.csv`. It consists of 731927 rows and 5 columns.See the table below for a detailed description.

|Column|Description|
|---|---|
|`'user_id'`	|User ID|
|`'recipe_id'`	|Recipe ID|
|`'date'`	|Date of interaction|
|`'rating'`	|Rating given|
|`'review'`	|Review text|