# Big-Data-Project-Regression-of-Movies-DS


## Documentation

[1- Architectures for Model Deployment](https://github.com/Azkaaaaaam/Big-Data-Project-Regression-of-Movies-DS/blob/46812faa30c1f3cdb5cb56cdd417e4cc6dafacee/Architectures%E2%80%94%20Big%20Data%20Project%20%20(1).pdf)

[2- Report - Detailed documentation](https://github.com/Azkaaaaaam/Big-Data-Project-Regression-of-Movies-DS/blob/46812faa30c1f3cdb5cb56cdd417e4cc6dafacee/Big%20Data%20-%20Movies%20Average%20Vote%20Prediction%20-%20Azza%20Kamoun%20(1).pdf)

[3- EDA - Storytelling](https://github.com/Azkaaaaaam/Big-Data-Project-Regression-of-Movies-DS/blob/46812faa30c1f3cdb5cb56cdd417e4cc6dafacee/_Movies%20Storytelling%20%E2%80%94%20Big%20Data%20Project%20.pdf)

[4- Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=links.csv)

## Summary

In our project, we aimed to predict the average rating of movies by using a dataset containing metadata for 45,000 films released on or before July 2017. We preprocessed the data extensively, including outlier detection and removal, feature engineering, and data scaling. In addition, we conducted exploratory data analysis to identify various factors such as the number of films released each year/month, the distribution of film ratings, the most popular genres, directors, actors, and keywords. 

- To predict the average rating, we used five different regression models: **Simple Linear Regression, Generalized Linear Regression, Random Forest, Gradient-Boosted Trees,** and **Decision Trees.** 

- We assessed each model's performance using various metrics such as **R squared (R2), Mean Absolute Error (MAE), and Root Mean SquaredError (RMSE)**. 

- The Random Forest model performed the best in terms of evaluation metrics, with an RMSE of 1.028797, an MSE of 1.0584244, and an R2 of 0.5905529. 
With an RMSE of 1.52205 and an R2 of 0.103821, the Simple Linear Regression model performed the worst. 

Our research has shown that using machine learning algorithms, the average rating of a movie can be predicted with a reasonable level of accuracy. We found no previous studies that focused on developing recommendation systems for this dataset, so our work is unique.
However, it is important to note that none of the previous works on the dataset were focused on developing regression models on this target variable, and almost all of them always focus on developing recommendation systems, which makes it difficult to compare our results with previous studies. Finally, this project demonstrates the potential of using machine learning to predict the success of films based on factors such as release date, genre, and cast. Our findings can help film producers and investors make informed decisions about which films to invest in and which films are likely to be successful.
