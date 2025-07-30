# CRFD-25
CRFD-25 is a newly constructed dataset to advance food and drink recommendation services for railway travelers. It contains representative dishes collected from 33 high railway traffic cities. In each city, more than 200 signature dishes are manually picked and labeled from different restaurants. The data is sourced from [Meituan](https://www.waimai.meituan.com) and [Dianping](https://www.dianping.com), two of the leading online food delivery platforms in China.

<img src="./website_en.png" style="max-width:100%;height:auto;">

# 🔍 Introduction
We have selected data from three major cities in China—Beijing, Shanghai, and Guangzhou—for both "food and drink.csv" and "restaurant.csv".<br>
## food and drink.csv
For the "food and drink.csv", we define 16 types of labels. For the intrinsic attribute, there are 8 attributes like city_id, restaurant_id, price, etc.
```bash
city_id:          The unique identifier of a city
restaurant_id:    The serial number of a restaurant 
food_id:          The unique identifier of food or drink
food_name:        The name of food or drink
price:            The price of food or drink
is_dinner:        Whether the food or drink is a main meal
food_type:        The type of food or drink
cuisine:          The cuisine of food or drink
```
There are 31 provincial regions in the dataset, which serve as tags to mark if food and drink suit people in each province.
```bash
The tags are rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
Beijing:          The extent to which people in Beijing like it
Tianjin:          The extent to which people in Tianjin like it
Hebei:            The extent to which people in Hebei like it
```
There are 4 spiciness tags in the dataset, used to mark the spiciness level of food.
```bash
The tags are divided into 0 and 1, where 0 indicates "no" and 1 indicates "yes".
not_spicy:        Whether the food or drink is not_spicy
slightly-spicy:   Whether the food or drink is slightly-spicy
medium-spicy:     Whether the food or drink is medium-spicy
extra-spicy:      Whether the food or drink is extra-spicy
```
There are 5 age tags in the dataset, used to mark whether food or drink suits people of each age group.
```bash
The tags are rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
Child ranges from 0-5. Teenager ranges from 6-17. Adult ranges from 18-34. Middle-ager ranges from 35-49. Elderly is above 50.
child:            The extent to which food and drink is suitable for children
teenager:         The extent to which food and drink is suitable for teenager
adult:            The extent to which food and drink is suitable for adults
middle-ager:      The extent to which food and drink is suitable for middler-agers
elderly:          The extent to which food and drink is suitable for elderly
```
There are 5 time-period tags in the dataset, used to mark whether food and drink are suitable for consumption in the corresponding time periods.
```bash
The tags are rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
breakfast:        The extent to which food and drink is suitable for breakfast
lunch:            The extent to which food and drink is suitable for lunch
dinner:           The extent to which food and drink is suitable for dinner
afternoon-tea:    The extent to which food and drink is suitable for afternoon-tea
night-snack:      The extent to which food and drink is suitable for night-snack
```
There are 2 gender tags in the dataset, used to mark whether food and drink suit people of each gender group.
```bash
The tags are rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
male:             The extent to which food and drink is suitable for male
female:           The extent to which food and drink is suitable for female
```
There are 4 season tags in the dataset, used to mark whether food and drink are suitable for consumption in the corresponding seasons.
```bash
The tags are rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
spring:           The extent to which food and drink is suitable in spring
summer:           The extent to which food and drink is suitable in summer
autumn:           The extent to which food and drink is suitable in autumn
winter:           The extent to which food and drink is suitable in winter
```
The food_score tag shows the sore of food and drink.
```bash
The tag is rated from 1 to 5, where 1 indicates the least recommended and 5 indicates the most recommended.
food_score:       The score of food or drink 
```
The image_name tag shows the image names of food and drink.
```bash
The image_name format: 1-1-1.jpg (in the order of city-restaurant-dish)
image_name:       The name of image 
```
## restaurant.csv
Most of the tags are the same as “food and drink.csv”. Here, only different ones are displayed.

For the intrinsic attribute, there are 7 attributes like restaurant_name, city_id, restaurant_id, etc.
```bash
restaurant_name:       The name of a restaurant
city_id:               The unique identifier of a city
restaurant_id:         The unique identifier of a restaurant 
province_id:           The unique identifier of a province 
average_price:         The average price of a restaurant 
average_score:         The average score of a restaurant 
restaurant_type:       The type of a restaurant 
```
The price tag shows the average price range of a restaurant.
```bash
The tags are divided into 5 tiers, where Tier 1 is 0-20, Tier 2 is 20-30, Tier 3 is 30-50, Tier 4 is 40-70 and Tier 5 is above 70.
price:                 The restaurant average price range
```
The is_chain tag shows wheather the restaurant is a chain store.
```bash
The tags are divided into 0 and 1, where 0 indicates "no" and 1 indicates "yes".
is_chain:              Whether the restaurant is a chain store.
```

CRFD-25 dataset is introduced in our paper which presents [LLM4Rail](https://anonymous.4open.science/r/LLM4Rail), an LLM-based railway service consulting platform.

# 📋 Acquire The Complete Dataset 
If you want to acquire the complete dataset, please send an email to xxxxx
