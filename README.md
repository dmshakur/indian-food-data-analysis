# Indian food data analysis project

## Introduction
**Project Duration**: December 10th to

### Participant Information
- **Name**: D'angelo Shakur
- **Current Location**: Medellín, Colombia
- **Country of Origin**: United States
- **Contact**: 
  - Email: dangeloshakur@gmail.com
  - Phone: +57 321 450 7954 (Colombia)

### Files and file structure
- data/
    - map_of_regions_of_india.jpg
    - indian_food.csv
- figures/
- notebooks/
    - data_processing.ipynb
- README.md

### Data Source and Characteristics
- **Source**: [Indian food 101 on Kaggle](https://www.kaggle.com/datasets/nehaprabhavalkar/indian-food-101)
- **Size**: 244 KB
- **Structure**:
  - Rows: 255
  - Columns: 9 (name, ingredients, diet, prep_time, cook_time, flavor_profile, course, state, region)

## Purpose & personal reasons for doing this project
Given the data set, the purpose of this project is to imagine that I am going to start a restaurant.
Looking at the data I want to find out what is a cost and ingredient effective and efficient way
to create a menu. Seeing as how ingredients are one of the main expenses, bringing cost down is important to
increase the financial efficiency of a business.

#### Indian food and me
I love Indian food, and when it is made the right way it is to die for. 
I have always loved curry, and because of that at the start of the pandemic I decided to learn how to cook, indian food.
Not entirely Indian food, I usually stick to any foods between India and Morocco as they tend to use similar ingredients.
And it is a lot easier to cook foods from similar cuisines, in terms of ingredients, than to cook an Italian dish one day, a japanese one, 
and then an Indian dish the other, you could spend a lot of money on only a few meals.

### Why do this project
This project is merely an exercise to improve upon my skills as a data analyst. But I love Indian food, and I do think that if I really
wanted to I could open up my own Indian restaurant, my vision is to have something small, with a small menu, where we take pride in
making everything perfect. Smaller menu = less stress = more success = more perfection, at least that is my thinking. So taking on this project
is almost like an exercise of the imagination, of imagining what could be with a potential restaurant, and one thing I do know is that common, inexpensive
or shared ingredients between dishes in a menu reduces expenses, and should in theory increase profit, as well as give the restraunteer the ability to 
lower their prices more so that they would be more accessible to all.

## Data processing
Upon initially looking at the data for the most part it looked fine, but there were some issues that needed to be dealt with. Such as -1 values being apparent in about half of the columns. I used internet search to find information for replacing -1 values for region, state, and cooking time. Other than that little was done to change the dataframe other than making everything lower case to make it a little more uniform. And finally I saved the dataframe into a new csv file.

I had originally downloaded a csv file containing prices for indian foods, but after some looking around in the file I found that there were actually very few varieties of foods in that csv rendering it useless.

## Exploratory data analysis
To start out with, I identified a goal, to create a menu of dishes to serve in an imaginary indian restaurant. This menu needed to have a few things:
1. Meat: I have trouble digesting many plants, and as a result meat is central to my diet.
2. Faster cooking time: Having faster cooking time reduces workload, stress, etc.
3. Having common ingredients: Nice to not have to buy many different ingredients for many different dishes.
4. A variety of different dishes for different courses.

#### Cooking time
Upon Looking at the data for cooking time I was able to find a suitable menu using the data provided. I looked at the data for the items with the fastest cooking time and did an internet search to gauge popularity, and then made choices based on personal preference, based on the dishes that were considered most popular by the internet. I also then added some dishes that I thought would be a good addition to that as well.

#### Ingredients
The data for ingredients was very flawed, and completely useless. I know from the experience of cooking Indian food almost exclusively for a few years now that the ingredient list for most dishes is pretty long, especially when it comes to spices. For example, garlic is not in the top 20 most used ingredients in the dishes for this data set, which is not possible. So unfortunately that data being unworthy of being used without researching and looking up recipes and manually inputing everything, I could do nothing further with it.

## Conclusion
To conclude a decent menu was made based on data where cooking time was concerned. It consisted of 4 items in each category, vegetarian, meat, starter/snacks and desserts. Some items I added that were not among the fastest cooking dishes for reasons of personal preference and popularity. Most of the dishes originated in the northern area of India, and the most common origin state was Punjab.

## Acknowledgments
Special thanks to my mentor, Logapriya Viswanathan, for her invaluable guidance and support throughout this project.
