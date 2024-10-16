# FoodTracker


### 💠Data collection
Data were collected from the diets of four individuals from 01/01/2023 to 22/01/2023. 

### 💠Dataset Information
Data operations separated into 4 tables.
1. Channel consists of columns : ChannelName and ChannelID
2. Fooddetails consists of columns : Menu and Category
3. Foodtracker consists of columns : record_num, memberID, date, meal, menu, channel, and shopName, price
4. Memberdetails consists of columns : memberID, Name, Gender, Weight, and Height

You can see the relationship of the data in the image below.

<img src="https://github.com/ChawitTe/FoodTracker/blob/main/JTM_database.png" style="width:300px;">

### 💠Data analysis tools and methods
Creating a database to store data uses MySQL Workbench. Then use Python connect to MySQL Workbench to analyze the data to find insights from the database.

### 💠 Data Analysis Results
From the data, it is possible to analyze and find insights from the data to answer many questions, such as:
1. How much does each member spend on food that contains no more than xxx calories per piece?
2. What are the total prices of each type of food, total calories, number of orders of this type of food, and average calories per order?
3. How many calories does each member eat at each meal?
4. How many times did each member order food through various channels?
5. How many times did each member order different dishes?
