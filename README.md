# CRFD-25
CRFD-25 is a newly constructed dataset to advance food and drink recommendation services for railway travelers. It contains representative dishes collected from 33 high railway traffic cities. In each city, more than 200 signature dishes are manually picked and labeled from different restaurants. The data is sourced from [Meituan](https://www.waimai.meituan.com) and [Dianping](https://www.dianping.com), two of the leading online food delivery platforms in China.

<img src="./illustrationofCRFD-25dataset.jpg" style="max-width:100%;height:auto;">

# 🔍 Introduction
We show "food and drink.csv" and "restaurant.csv" of three main cities in China including Beijing,Shanghai and Guangzhou. <br>
## food and drink.csv
For the "food and drink.csv", we define 16 types of labels. For the intrinsic attribute, there are 8 attributes like city_id, restaurant_id, price, etc.
```bash
city_id:          The unique identifier of a city
restaurant_id:    The serial number of a restaurant 
food_id:          The unique identifier of food or drink
food_name:        The name of food or drink
price:            The price of food or drink
is_dinner:        Weather the food or drink is a main meal
food_type:        The type of food or drink
cuisine:          The cuisine of food or drink
```
province
```bash
Beijing:          The extent to which people in Beijing like it
Tianjin:          The extent to which people in Tianjin like it
Hebei:            The extent to which people in Hebei like it
```
spicy
```bash
not_spicy:        Weather the food or drink is not_spicy
slightly-spicy:   Weather the food or drink is slightly-spicy
medium-spicy:     Weather the food or drink is medium-spicy
extra-spicy:      Weather the food or drink is extra-spicy
```
age
```bash
child:            The extent to which is suitable for children
teenager:         The extent to which is suitable for teenager
adult:            The extent to which is suitable for adults
middle-ager:      The extent to which is suitable for middler-agers
elderly:          The extent to which is suitable for elderly
```
lunch
```bash
breakfast:        The extent to which is suitable for breakfast
lunch:            The extent to which is suitable for lunch
dinner:           The extent to which is suitable for dinner
afternoon-tea:    The extent to which is suitable for afternoon-tea
night-snack:      The extent to which is suitable for night-snack
```
sex
```bash
male:             The extent to which is suitable for male
female:           The extent to which is suitable for female
```
season
```bash
spring:           The extent to which is suitable in spring
summer:           The extent to which is suitable in summer
autumn:           The extent to which is suitable in autumn
winter:           The extent to which is suitable in winter
```
food_score
```bash
food_score:       The score of food or drink 
```
image_name
```bash
image_name:       The name of image 
```
## restaurant.csv
The difference lies in some intrinsic attributes of restaurants like restaurant_id, average_score, restaurant_type and so on.CRFD-25 dataset is introduced in our paper which presents [LLM4Rail](https://anonymous.4open.science/r/LLM4Rail), an LLM-based railway service consulting platform.

# 📋 Acquire The Complete Dataset 
If you want to acquire the complete dataset, please send an email to xxxxx
