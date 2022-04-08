# 🚙 Car Prices Prediction 

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction

There are a lot of __car manufacturers__ in the US. With the development of manufacturing units and tests, there are a lot of cars being manufactured with a lot of features. Therefore, innovators are coming with the latest developments in the field and they are ensuring that the drivers get the best experience going on a ride in these cars. 

![alt text](https://media.wired.com/photos/59547e60ce3e5e760d52d429/191:100/w_1280,c_limit/02_Bugatti-VGT_photo_ext_WEB.jpg)

## Business Contraints/Key Performance Metrics

However, one of the challenging aspects of running the sales for cars is to accurately give the __best price__ for cars which ensures that a lot of people buy them and there is a great demand because of this price. Factors that influence the price of cars are __mileage__, __car size__, __manufacturer__ and many others as well. But for humans to comprehensively decide the price is difficult especially when there are a lot of these features that influence the price. One of the solutions to this challenge is to use __machine learning__ and __data science__ to understand the insights and make valuable predictions which generate profits for the companies.  

<h2> Data Source</h2>

We would be working with quite a large data which contain about __10000__ data points where again we would be dividing that into training set and the test set. Having a look at some of the cars that we are always excited to use in our daily lives, it is better to understand how these cars are being sold and their average prices. Feel free to take a look at the dataset that was used in the process of predicting the prices of cars. Below is the link.

https://www.kaggle.com/CooperUnion/cardataset

## Machine Learning and Deep Learning

<p><strong>Machine Learning</strong> and <strong>deep learning</strong> have gained rapid traction in the recent decade. It would be really helpful if we are able to predict the prices of car based on a few set of features such as <strong>horsepower</strong>, <strong>make</strong> and <strong>other features</strong>. Imagine if a company wants to set the price of a car based on some of the features such as make, horsepower and mileage. It could do so with the help of machine learning models that would help it to determine the price of car. This would ensure that the company sets the right amount so that they get the most profits while setting such a price. Therefore, the machine learing models that we would be working with would ensure that right price is set to new cars which would save a lot of money for car manufacturers respectively. </p>

We would be working with the car prices prediction data and looking for the predictions of different kinds of cars. We would be first visualizing the data and understanding some of the information that is very important for predictions. We would be using different regression techniques to get the average price of the car under consideration.

## Metrics

Predicting the car prices is a __continuous machine learning problem__. Therefore, the following metrics that are useful for regression problems are taken into account. Below are the __metrics__ that were used in the process of predicting of car prices.

* [__Mean Squared Error (MSE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)
* [__Mean Absolute Error (MAE)__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

## Exploratory Data Analysis (EDA)

In this section of the project, the data is explored to see the patterns and trends and observe interesting insights. Below are some interesting observations generated.

* A large number of cars were from the manufacturer __'Chevrolet'__ followed by __'Ford'__. 
* The total number of cars manufactured during the year __2015__ were the highest in all the years found on the data.
* There were many missing values for __'Market Category'__ feature and a few missing values for the features __'Engine HP'__ and __'Engine Cylinders'__.
* The average prices of the cars were the highest in the year __2014__ and lowest in the year __1990__ from the data. 
* The prices of __'Bugatti'__ manufacturer are extremely high compared to the other car manufacturers.  
* __'Bugatti'__ manufacturer also had an extremely high value for the horsepower (HP) based on the graphs in the notebook.
* There is a __negative correlation__ between the feature __'City Mileage'__ and other features such as __'Engine Cylinders'__ and __'Engine HP'__. This is true because higher the mileage of the car, there is a higher probability that the total number of cylinders and engine horsepower would be low. 

## Machine Learning Models 

We have to be using various machine learning models to see which model reduces the __mean absolute error (MAE)__ or __mean squared error (MSE)__ on the cross-validation data respectively. Below are the various machine learning models used. 

| __Machine Learning Models__| __Mean Absolute Error__| __Mean Squared Error__|
| :-:| :-:| :-:|
| [1. Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)| 6737| 364527989|
| [2. Support Vector Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)|	22525|	2653742304|
|	[3. K Nearest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)|	4668|	198923161|
|	[4. PLS Regression](https://scikit-learn.org/stable/modules/generated/sklearn.cross_decomposition.PLSRegression.html)|	6732|	364661296|
|	[5. Decision Tree Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)|	__3327__|	135789622|
|	[6. Gradient Boosting Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)|	4432|	175275369|
|	[7. MLP Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)|	6467|	250908327|

## Outcomes

* The best model that was performing the best in terms of __mean absolute error (MAE)__ and __mean squared error (MSE)__ was __Decision Tree Regressor__.
* __Exploratory Data Analysis (EDA)__ revealed that __Bugatti manufacturer's prices__ were significantly higher than the other manufacturers. 
* __Scatterplots__ between the __actual prices__ and __predicted prices__ were almost __linear__, especially for the __Decision Tree Regressor__ model.

## Future Scope

* It would be great if the best __machine learning model (Decision Tree Regressor)__ is integrated in the live application where a __seller__ is able to add details such as the __manufacturer__, __year of manufacture__ and __engine cylinders__ to determine the best price for cars that generates __large profit margins__ for the seller. 
* Adding __additional data points__ and __features__ could help in also better determining the best prices for the latest cars as well. 

## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git that could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link of the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(18).png" width = "600" />

5. The link of the repository can be found when you click on "Code" (Green button) and then, there would be a html link just below. Therefore, the command to download a particular repository should be "Git clone html" where the html is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(20).png" width = "600" />

8. Later, open the jupyter notebook by writing "jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 



