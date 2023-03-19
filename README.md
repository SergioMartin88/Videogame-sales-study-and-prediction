# Comparison of Video Game Market Analysis and Prediction using DecicionTree Regressor (with and without GridSearch) and Catboost Regressor
 Author: Sergio Martin

In this project I extracted a dataset to study what videogames are more succesful in terms of sales and reviews. During this project, I considered different factors, such as the genre, platforms, distributors, ratings, etc.

The dataset used was collected from [RAWG](https://www.kaggle.com/datasets/jummyegg/rawg-game-dataset) and contains 474417 video games from over 50 platforms.

In order to have a first approach into the matter, I represented the data using different libraries such as Matplotlib and Seaborn in order to have an idea of what makes a videogame more likely to have a larger volume of sales.

After that, I trained the model using 3 different machine learning methods and comparing the likelihood to predict the sales volume of the different methods. The different methods used were **DecessionTree Regressor**, **with and without GridSearch** and **CatBoost Regressor**.

The **CatBoost Regressor** model trained was able to predict very high percentage of accuracy (89%).