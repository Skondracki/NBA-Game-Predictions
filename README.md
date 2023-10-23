# NBA-Game-Predictions

## Project Description

This project was part of a final capstone assignment in a machine learning course at the Universidad de San Francisco Quito in Quito, Ecuador. The NBA Game Outcome Predictor is a machine learning project designed to forecast the results of NBA basketball games. It leverages historical game data to predict whether a team will win or lose its next game and provides estimates for the game's final score. This project aims to assist sportsbook operators in setting odds and improve the overall accuracy of outcome predictions in the highly competitive world of sports betting.

## Why This Project?

Sports betting is an increasingly popular industry with a constant need for accurate game outcome predictions. This project serves to demonstrate how machine learning techniques can be used to make informed predictions, which can be crucial for sportsbook businesses.

## How to Run the Code

1. Begin by opening Google Colab in your web browser and log in to your Google account.

2. Mount your Google Drive using the provided code. This will grant Colab access to your Drive.

3. Install the necessary libraries by running !pip3 install scikeras pandas.

4. Upload your game.csv file to your Google Drive and update the path in the code accordingly.

5. Execute each code cell in sequence to load, preprocess, and analyze the data.

6. Review the generated visualizations for insights into the dataset.

7. Follow the code instructions to build and evaluate models for classification and regression tasks. To understand how to use the models follow the example usage below. 

9. Execute the hypothesis test cell to assess the significance of the model differences.

Please note that these instructions assume you're using Google Colab. If you're using a different environment, such as Jupyter Notebook, you'll need to adapt the file loading and setup steps accordingly.

## Features and Technologies

- Utilizes the NBA database with 50+ years of game data.
- Implements data preprocessing techniques to clean and prepare the dataset.
- Builds classification and regression models for outcome and score predictions.
- Utilizes machine learning techniques such as neural networks and k-nearest neighbors.
- Hypothesis testing to assess model improvements.

## How to Use the Project 
The project includes both classification and regression models. The classification model predicts whether a team will win or lose its next game, while the regression model estimates the final score of the game.

Example Usage
Code Example: Classification Model
### Classification model usage example
```
matches = {
    'MIA-NYK': [[0.46, 0.344, 30.9, 40.6, 23.8, 0.47, 0.354, 34, 46.6, 22.9]],
    'GSW-LAL': [[0.479, 0.385, 34.1, 44.6, 29.8, 0.482, 0.346, 35.7, 45.7, 25.3]]
}

print(classifier_opt.predict(matches['MIA-NYK']))
print(classifier_opt.predict(matches['GSW-LAL']))
```
Code Example: Regression Model
### Regression model usage example
```
matches = {
    'MIA-NYK': [[0.46, 0.344, 30.9, 40.6, 23.8, 0.47, 0.354, 34, 46.6, 22.9]],
    'GSW-LAL': [[0.479, 0.385, 34.1, 44.6, 29.8, 0.482, 0.346, 35.7, 45.7, 25.3]]
}

print(regresser.predict(matches['MIA-NYK']))
print(regresser2.predict(matches['MIA-NYK']))
print(regresser.predict(matches['GSW-LAL']))
print(regresser2.predict(matches['GSW-LAL']))
```

## Project Credits 

This project was developed by the following team members:
Luis Cagigal 
Luis Astudillo
Sean Kondracki

## License
This project is licensed under the MIT License.

