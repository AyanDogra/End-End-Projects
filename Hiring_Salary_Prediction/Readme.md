# Salary Prediction
This model predicts salary using an ml model

## Project Structure:
This project has four major parts:-
* Model.ipynb-This contains the code for the Machine Learning model to predict employee salary based on data present in 'hiring.csv' file.
* app.py- This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
* templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
* Procfile and requirements.txt- These are required for deployement on Heroku

## Project Deployement
This project can be deployed locally at URL: http://localhost:5000 and has been deployed on heroku at:https://salary-prediction-101.herokuapp.com

