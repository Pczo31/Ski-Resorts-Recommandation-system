
![ecg.jpeg](https://www.bing.com/images/search?view=detailV2&ccid=tdAYGtxo&id=DAACE2BBA65E77B1BF302FAA1904FE7FA32729C0&thid=OIP.tdAYGtxoaFEGq-aQCAmVmwHaD4&mediaurl=https%3A%2F%2Fth.bing.com%2Fth%2Fid%2FR.b5d0181adc68685106abe6900809959b%3Frik%3DwCkno3%252f%252bBBmqLw%26riu%3Dhttp%253a%252f%252f2.bp.blogspot.com%252f-hAnpo8RW9T8%252fVddC9vmKx_I%252fAAAAAAAACKk%252fqiHXwDKA_lg%252fw1200-h630-p-k-no-nu%252fzermatt-valley-switzerland.jpg%26ehk%3DgnEHfZEciXdHYNc%252bcRjLIQ1qiBVRkvB7XEa1dj79aXw%253d%26risl%3D%26pid%3DImgRaw%26r%3D0&exph=630&expw=1200&q=zermatt+switzerland&simid=608043785956524017&form=IRPRST&ck=A24973DAC1A6195789F0B80B0B512132&selectedindex=12&ajaxhist=0&ajaxserp=0&vt=0&sim=11)


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