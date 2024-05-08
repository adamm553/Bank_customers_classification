# Projekt RR

Author: Adam Piątek
Date: 2023-06-07

This project involves building a decision tree model to predict whether a customer will subscribe to a term deposit based on various features such as age, balance, duration of the last contact, etc.

## Overview

The project includes the following steps:

1. Importing libraries such as dplyr, rpart, rpart.plot, and caret.
2. Loading the dataset (`bank.csv`).
3. Exploring and preprocessing the data.
4. Splitting the dataset into training and testing sets.
5. Building a decision tree model using the rpart package.
6. Evaluating the model's performance using confusion matrix and accuracy metrics.

## Usage

To run the project:

1. Clone the repository to your local machine.
2. Ensure you have R and RStudio installed.
3. Open the R Markdown file (`Projekt_RR.Rmd`) in RStudio.
4. Knit the R Markdown file to generate the HTML output.

## Data Source

The dataset used for this project is `bank.csv`.

## Libraries Used

- dplyr
- rpart
- rpart.plot
- caret
- caTools

You can install these libraries in R using the `install.packages()` function.

## Results

The decision tree model achieved an accuracy of approximately 88.2% on the test set, indicating good predictive performance.

## Author

This project was conducted by Adam Piątek.

If you have any questions or feedback, feel free to reach out!
