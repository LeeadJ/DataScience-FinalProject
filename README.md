# DataScience Final Project Semester B
Leead Jacobowitz

## Part 1: Improving Previous Classification Dataset
- **Dataset:** Flight Passenger Satisfaction Database (Kaggle) 
- Imported and cleaned the data (removed noise).
- Using Visual plots in order to recognize connection between different features.
- Initially examined two diferent models: Knn and Logistic Regression.
- Cross-Validiation Score: Knn (69%), Logistic Regression (87%).
- Using the XGBoost model I improved the Accuracy Score to 90%.
![image](https://user-images.githubusercontent.com/77110578/180454851-66068472-1367-4c91-a7c5-4ddf77d14905.png)
![image](https://user-images.githubusercontent.com/77110578/180455133-87a6d5f9-7bd1-4255-b029-5dea72fd4729.png)

## Part 2: Fashion-MNIST Dataset
- In this project, the goal was to build a classifying model for the Fashion-MNIST dataset. 
- Using PCA I was able to decrease the number of dimensions to 187, which allowed the model to simplify and be more efficient.
- Used XGBoost and recieved a total Accuracy Score of 88%.

## Part 3: Cats-vs-Dogs Dataset
- In this project, the goal was to build a classifying model for the Cats-vs-Dogs dataset. 
- Using PCA I was able to decrease the number of dimensions to 80, which allowed the model to simplify and be more efficient.
- Used XGBoost and recieved a total Accuracy Score of 63%. (Which is considered good).

## Part 4: Hand Position Dataset
- In this project, the goal was to classify different hand positions.
- After cleaning the data and loading it, I ran models like Knn, Logistic Regression, Forest Regression, Naive Bayes, Bagging, Voting and XGBoost.
- I split the testing data into training and testing sets in order to determine which was the best model for the classification. 



