Weather Prediction – Machine Learning Project

This project uses the "Seattle Weather dataset" to build a simple machine learning model that predicts whether it will rain based on features like temperature, wind, and humidity.

The project includes:
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Applying a beginner-friendly ML model (Logistic Regression)  
- Evaluating model accuracy  
- A basic prediction function using user input  

---

Project Files

Final Project File 
Weather_Prediction_final.ipynb 
This is the latest, clean, and final implementation of the project.

Older Work (Draft)
weather_prediction_L&T.ipynb*  
This file contains earlier attempts and scratch work.  
It is kept for transparency and version history.

---

Dataset
The project uses the "Seattle Weather CSV dataset", containing daily weather observations such as:
- Temperature  
- Precipitation  
- Wind  
- Weather conditions  

---

How the Model Works
A beginner-friendly model (Logistic Regression) is trained to classify whether it will **rain or not**.

Steps included:
1. Load the dataset  
2. Clean missing values  
3. Encode categorical columns  
4. Train-test split  
5. Train the model  
6. Predict & evaluate  
7. Live prediction using user input (temperature, wind, etc.)

---

Accuracy
Model accuracy varies between 80–85% depending on preprocessing and features used.

---

Live Prediction Example
You can run the notebook to enter:
- Temperature  
- Wind  
- Humidity  
- Weather type  

And the model returns:  
The trained model instantly predicts the weather condition like sun, rain, or fog

---

Note for Reviewers
Please refer to the "final project file" for the clean and updated implementation:
👉 Weather_Prediction_final.ipynb

Older versions are retained only for reference.

F1 score: 0.64

Precision: 0.61

Recall: 0.70

Live prediction
