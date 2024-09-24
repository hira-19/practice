
# Machine Learning Portfolio Project
## Titanic Dataset - Predictive Model for Survival


## Project Overview:- 
#### Goal:- 
* The goal of this project is to build and deploy a predictive model to estimate the likelihood of survival on the Titanic based on attributes such as age, sex, class, and fare.

#### Deployment Links: 
- Hugging Face Deployment: [Your Hugging Face URL]
- GitHub Repository: [Your GitHub URL]

## Objectives:-
#### Primary Goal: 
- Develop a predictive model using decision tree to estimate if the input data has been survived or not.

#### Deployment:
-  Create a FastAPI application to serve the model and a Gradio UI for user interaction, deployed on Hugging Face Spaces.

## Methodology
### Data Preprocessing:

#### Handling Missing Data:
- Addressed missing values in age and embarked features.
- Encoding Categorical Variables: Applied one-hot encoding for categorical variables.
- Standardizing Numerical Features: Scaled age and fare.


#### Exploratory Data Analysis (EDA):

#### Variable Distributions:
- Analyzed distributions of key variables such as age, fare, and survival.
#### Feature Relationships:
- Investigated relationships between features and survival status.


#### Model Development:

#### Data Splitting:
- Divided the dataset into training (70%) and testing (30%).
Model Implementation:
- Linear Regression: Developed and trained the model to predict survival probability.
- Random Forest: Developed and trained a random forest model for improved accuracy.

Model Evaluation:
- Linear Regression: Evaluated using R-squared and Mean Squared Error.
- Random Forest: Evaluated using accuracy, precision, and recall.


#### FastAPI Application:

API Creation:
- Developed a FastAPI application to serve the trained model.

Endpoint Implementation:
- Created an endpoint for input data, model predictions, and results.


#### Deployment:

####  1. Gradio UI:
- Developed a user-friendly interface for model interaction.
####  2. Hugging Face Deployment:
- Deployed the application on Hugging Face Spaces.

