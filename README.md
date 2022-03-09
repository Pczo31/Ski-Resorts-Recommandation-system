![header readme](https://user-images.githubusercontent.com/92397725/157523602-09bb8da9-154d-43b7-99ac-d471935426f2.jpg)


# Ski Resorts of Europe
By:Piotr Czolpik

# Overview
In this project, I built a ski recommendation system using Ski-resort-stats.com. I develop a resort based recommendation model using KNN and cosine similarity and a Kmeans model.

# Business Overview
I was hired by Ski Europe Travel Agency to help them get a better understanding of which country and resort have similiar features for them to have more recommendations for thier clients. For example if you went to Zermatt Switzerland and you want to experience the same moutain type but in a different country they can recommed which ones is most similiar to that. I also provided which countries are most family friendly with the most begginer slopes or which resorts to go to for more advanced. Also stated which country to go to for the money saving but best overall experience.

# Data
  [Skidata](https://ski-resort-stats.com/)
I used ski data from "Ski Resort Stats" which includes over 20 countries and over 300 resorts. The dataset contains Countrys, Resorts, Total Slopes, Total Lifts, etc.

# Train - Test Split

The key purpose of splitting the dataset into training and test sets is to estimate how well the learned model will generalize to new data. For this reason, the train - test split is an essential component of building models.



# Models

To build my recommendation system I used KNN,Kmeans,DummyRegressor,LinearRegression, also bar charts to show the top countries and thier total slopes.

The following charts are 

![regressorchart](https://github.com/Pczo31/Capstone/blob/main/images/regressor%20chart.png)

![withoutstandarized](https://github.com/Pczo31/Capstone/blob/main/images/Without%20standardization.png)
![with](https://github.com/Pczo31/Capstone/blob/main/images/standardizedchart.png)




The bar charts represent the top 10 countries that show how many ski resorts they have in total. The day pass chart shows which country has the most expensive lift ticket per day.I also included the top countries with the most slopes in total.Finally the last chart shows which country has the highest eak

![top10](https://github.com/Pczo31/Capstone/blob/main/images/top%2010%20barchart.png)
![Daypass](https://github.com/Pczo31/Capstone/blob/main/images/price%20barchart.png)
![totalslopes](https://github.com/Pczo31/Capstone/blob/main/images/totalslopes%20barchart.png)
![higestpeak](https://github.com/Pczo31/Capstone/blob/main/images/highest%20barchart.png)





We are especially interested in the R-squared value, since it tells us what proportion of the variability of y around its mean can be explained by the model. This number falls between 0 and 1, and a higher value indicates greater power in prediction. Here we go!


# Conclusion
With the recommendation system it is easier for clients to have an understanding of which resports in Europe are similiar to each other. Now clients can know what country is more family freindly, or which country is more advanced. I did a break down of every country with charts provided to make it easier to understand.


## Next Step
I would like to expand on this recommendation system by including all the ski resorts world wide to give a better system across all aspects. I am also working on a website to make it easier for people just to go on it and put in the features they would like and country they would like to go to and get the perfect match for them and thier family.
