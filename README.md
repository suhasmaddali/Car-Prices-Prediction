# 🚙 Car Prices Prediction 

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction

There are a lot of __car manufacturers__ in the US. With the development of manufacturing units and tests, there are a lot of cars being manufactured with a lot of features. Therefore, innovators are coming up with the latest developments in the field and they are ensuring that the drivers get the best experience going on a ride in these cars.

<img src = "https://media.wired.com/photos/59547e60ce3e5e760d52d429/191:100/w_1280,c_limit/02_Bugatti-VGT_photo_ext_WEB.jpg" width = 350 height = 200/><img src = "https://github.com/suhasmaddali/Images/blob/main/Car%20Prices%20Prediction%20GitHub%20Image.jpg" width = 350 height = 200/>

<img src = "https://github.com/suhasmaddali/Images/blob/main/Car%20Prices%20Prediction%20GitHub%20Image%202.jpg" width = 350 height = 200/><img src = "https://github.com/suhasmaddali/Images/blob/main/Car%20Prices%20Prediction%20GitHub%20Image%203.jpg" width = 350 height = 200/>

## Business Constraints / Key Performance Metrics (KPIs)

However, one of the challenging aspects of running the sales for cars is to accurately give the __best price__ for cars which ensures that a lot of people buy them and there is a great demand because of this price. Factors that influence the price of cars are __mileage__, __car size__, __manufacturer__, and many others as well. But for humans to comprehensively decide the price is difficult especially when there are a lot of these features that influence the price. One of the solutions to this challenge is to use __machine learning__ and __data science__ to understand insights and make valuable predictions that generate profits for the companies. 

## Machine Learning and Deep Learning

* __Machine Learning__ and __deep learning__ have gained rapid traction in the recent decade. 
* It would be really helpful if we can predict the prices of a car based on a few sets of features such as __horsepower__, __make__ and __other features__. 
* Imagine if a company wants to set the price of a car based on some of the features such as make, horsepower, and mileage. 
* It could do so with the help of machine learning models that would help it to determine the price of a car. 
* This would ensure that the company sets the right amount so that they get the most profits while setting such a price. 
* Therefore, the machine learning models that we would be working with would ensure that the right price is set for new cars which would save a lot of money for car manufacturers respectively.
* We would be working with the car prices prediction data and looking for the predictions of different kinds of cars. 
* We would be first visualizing the data and understanding some of the information that is very important for predictions. 
* We would be using different regression techniques to get the average price of the car under consideration.

<h2> Data Source</h2>

* We would be working with quite a large data which contains about __10000__ data points where again we would be dividing that into the training set and the test set.
* Having a look at some of the cars that we are always excited to use in our daily lives, it is better to understand how these cars are being sold and their average prices. 
* Feel free to take a look at the dataset that was used in the process of predicting the prices of cars. Below is the link.

__Source:__ https://www.kaggle.com/CooperUnion/cardataset

## Metrics

Predicting car prices is a __continuous machine learning problem__. Therefore, the following metrics that are useful for regression problems are taken into account. Below are the __metrics__ that was used in the process of predicting car prices.

* [__Mean Squared Error (MSE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)
* [__Mean Absolute Error (MAE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

## Exploratory Data Analysis (EDA)

In this section of the project, the data is explored to see the patterns and trends and observe interesting insights. Below are some interesting observations generated.

* A large number of cars were from the manufacturer __'Chevrolet'__ followed by __'Ford'__. 
* The total number of cars manufactured during the year __2015__ was the highest in all the years found on the data.
* There were many missing values for __'Market Category'__ feature and a few missing values for the features __'Engine HP'__ and __'Engine Cylinders'__.
* The average prices of the cars were the highest in the year __2014__ and lowest in the year __1990__ from the data. 
* The prices of __'Bugatti'__ manufacturer are extremely high compared to the other car manufacturers.  
* __'Bugatti'__ manufacturer also had an extremely high value for horsepower (HP) based on the graphs in the notebook.
* There is a __negative correlation__ between the feature __'City Mileage'__ and other features such as __'Engine Cylinders'__ and __'Engine HP'__. This is true because the higher the mileage of the car, there is higher the probability that the total number of cylinders and engine horsepower would be low. 

<h2> Visualizations</h2>

Looking at the dataset, it can be seen that there are categories such as Vehicle Size, city mpg, popularity, and transmission types. There are other features that we would explore in visualizations. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Data%20Image.png"/>

We will be taking a look at a list of visualizations that can give us an understanding of the data. 
Exploring the count of various car companies available in the dataset, it is seen that Chevrolet has the highest number of cars followed by Ford. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Total%20Cars%20Count.png"/>

With the progress in years, there is an increase in the demand for cars sold. This is clearly demonstrated in the visualization. In addition, our ML models would perform well on the most recent cars as we have more data in this category. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Cars%20Sold.png"/>

Most of the cars are automatic as depicted in the plot. There are fewer manual cars compared to automatic cars. There are also a few unknown categories. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Transmission%20type%20countplot.png"/>

Most of the cars have a regular unleaded engine type. There are also electric cars in our categories. Since electric cars are new, they are low in number in the dataset. There are a few car categories that use diesel or other types of fuels. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Engine%20type%20countplot.png"/>

A large portion of cars are compact vehicle-size cars. But we tend to see that there is quite an equal distribution of cars amount the various vehicle size categories. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Countplot%20of%20vehicle%20size.png"/>

Missingno plots are useful to help us determine the total number of missing values in the dataset. There are missing values in categories such as 'Market Category' and 'Engine HP'. Based on this information, steps are taken to either impute the missing values or remove them so that they do not have an impact on the ML model performance of determining the prices of cars. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Missingno%20plot.png"/>

The overall prices of cars were the highest for the year '2014' compared to other years. The next highest average prices of cars are in the year '2012'. The lowest prices of cars are in the year '1990'. Hence, the year is a useful feature in determining car prices based on the plot below. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Avg%20car%20prices%20per%20year%20plot.png"/>

Cars that have both automatic and manual transmission has the highest average prices for all the years. This is followed by only automatic transmission-type cars. There are a few unknown categories that must be either removed or converted to a category as they do not aid in helping to understand the transmission type of cars.  

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Avg%20prices%20per%20transmission%20plot.png"/>

The average prices of cars for companies such as Bugatti and Maybach are the highest. There is a significant difference in terms of price for companies such as Bugatti vs other cars. This is true in real life because of their popularity in the modern world. Some of the most expensive brands, according to the plot, include Bugatti, Maybach, Rolls-Royce, Lamborghini, Bentley, McLaren, and Ferrari. You can explore the plot to understand the average car prices for various car brands. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/avg%20prices%20per%20company%20plot.png"/>

This is a bar chart highlighting the horsepower of various car manufacturers. Without surprise, Bugatti has the highest horsepower despite having a higher price as compared to other brands. This was followed by McLaren and Mayback. These cars typically are the best in class when it comes to delivering performance. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Horsepower%20plot.png"/>

Car brands such as Ford and BMW are highly popular. Other popular brands include Audi, Ferrari, Honda, and Nissan. It can be interesting to see how much of an impact the popularity of cars has on car prices for various brands. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Popularity%20plot.png"/>

The plots on the left below show the highway MPG for all the cars in the dataset. Based on this, it is seen that there are quite a few outliers in the data. Therefore, steps are taken to remove them. 

The plots on the right show the highway MPG feature after removing the outliers from the data. In this way, the best ML model learns these features and represents them to make predictions about car prices. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Highway%20mgp.png"/><img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Highway%20mpg%20outliers%20removed.png"/>

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Cith%20mpg.png"/><img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/City%20mpg%20outliers%20removed.png"/>

As evident in real-life, highway MPG for a particular car tends to be higher than the city MPG. This is reflected in this plot as there is a difference in the spread and the mean for each of the categories. There are still a few outliers but we will consider some of them and get the performance of models. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/City%20Vs%20Highway%20boxplot.png"/>

Building a heatmap of the correlation matrix, it is seen that engine horsepower and engine cylinders are closely related. In addition, features such as city mpg and highway mpg are also correlated with each other. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Heatmap%20correlation.png"/>

### Model Performance

We will now focus our attention on the performance of __various models__ on the test data. Scatterplots can help us determine how much of a spread our predictions are from the actual values. Let us go over the performance of many ML models used in our problem of car price prediction. 

[__Linear Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) - After looking at the linear regression plot, it looks like the model is performing quite well. Scatterplots between the predictions and the actual test outputs closely resemble each other. If there are low latency requirements for a deployment setup, linear regression could be used. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/LR%20Plot.png"/>

[__Support Vector Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html) - Support vector regression (SVR) can be computational. In addition, the results below indicate that the predictions are far off from the actual car prices. Therefore, alternate models can be explored. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/SVR%20Plot.png"/>

[__K Nearest Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html) - K-Nearest Regressor is doing a good job in predicting the car prices as highlighted in the plot below. There is less spread between the test output labels and the predictions generated by the model. Therefore, there are higher chances that the model gives a low mean absolute error and mean squared error. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/K%20Neighbors%20Regressor.png"/>

[__PLS Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.cross_decomposition.PLSRegression.html) - This model does a good job overall when it comes to predicting car prices. However, it fails to compare trends and patterns for higher-priced cars well. This is evident due to the fact that there is a lot of spread among higher car price values as shown in the plot. K-Nearest Regressor, on the other hand, also does predictions accurately on higher priced cars. 
 
<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/PLS%20Regressor%20plot.png"/>

[__Decision Tree Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html) - Based on all the models tested, the decision tree regressor was performing the best. As shown below, there is a lot of overlap between the predictions and the actual test values. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Decision%20Tree%20Plot.png"/>

[__Gradient Boosting Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html) - The performance of gradient boosted decision regressor is plotted and it shows that it is quite similar to the decision tree. At prices that are extremely high, the model fails to capture the trend in the data. It does a good job overall. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/GBDT%20Plot.png"/>

[__MLP Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html) - It does a good job when it comes to predicting car prices. However, there are better models earlier that we can choose as their performance was better than MLP Regressor in this scenario. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/MLP%20Regressor%20plot.png"/>

[__Final Mean Absolute Error (MAE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html) - After performing feature engineering and hyperparameter tuning the models, the best model that gave the least mean absolute error (lower is better) was Decision Tree Regressor. Other models such as Support Vector Regressors took a long time to train along with giving less optimum results. Along with good performance, Decision Tree Regressors are highly interpretable and they give a good understanding of how a model gave predictions and which feature was the most important for it to decide car prices. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Final%20MAE.png"/>

[__Final Mean Squared Error (MSE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html) - The performance of the Decision Tree Regressor was also the highest when using mean squared error as the output metric. While the Gradient Boosted Regressor came close to the performance of a Decision Tree Regressor, the latter is highly interpretable and easier to deploy in real time. Therefore, we can choose this model for deployment as it is performing consistently across a large variety of metrics. 

<img src = "https://github.com/suhasmaddali/Car-Prices-Prediction/blob/main/images/Final%20MSE.png"/>

## Machine Learning Models 

We have to be using various machine learning models to see which model reduces the __mean absolute error (MAE)__ or __mean squared error (MSE)__ on the cross-validation data respectively. Below are the various machine learning models used. 

| __Machine Learning Models__| __Mean Absolute Error__| __Mean Squared Error__|
| :-:| :-:| :-:|
| [__1. Linear Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)| 6737| 364527989|
| [__2. Support Vector Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)|	22525|	2653742304|
|	[__3. K Nearest Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)|	4668|	198923161|
|	[__4. PLS Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.cross_decomposition.PLSRegression.html)|	6732|	364661296|
|	[__5. Decision Tree Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)|	__3327__|	__135789622__|
|	[__6. Gradient Boosting Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)|	4432|	175275369|
|	[__7. MLP Regressor__](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)|	6467|	250908327|

## Outcomes

* The best model that was performing the best in terms of __mean absolute error (MAE)__ and __mean squared error (MSE)__ was __Decision Tree Regressor__.
* __Exploratory Data Analysis (EDA)__ revealed that __Bugatti manufacturer's prices__ were significantly higher than the other manufacturers. 
* __Scatterplots__ between the __actual prices__ and __predicted prices__ were almost __linear__, especially for the __Decision Tree Regressor__ model.

## Future Scope

* It would be great if the best __machine learning model (Decision Tree Regressor)__ is integrated in the live application where a __seller__ is able to add details such as the __manufacturer__, __year of manufacture__ and __engine cylinders__ to determine the best price for cars that generates __large profit margins__ for the seller. 
* Adding __additional data points__ and __features__ could help in also better determining the best prices for the latest cars as well. 

## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git which could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in the "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link to the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(18).png" width = "600" />

5. The link to the repository can be found when you click on "Code" (Green button) and then, there would be an HTML link just below. Therefore, the command to download a particular repository should be "Git clone HTML" where the HTML is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(20).png" width = "600" />

8. Later, open the Jupyter notebook by writing "Jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 



