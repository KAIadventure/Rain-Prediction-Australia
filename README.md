# Rain Prediction in Australia 🌧️

## Overview
This project is all about predicting whether it's going to rain tomorrow across various locations in Australia! I had some fun with machine learning by testing out five different models to see which one does the best job at forecasting the rain.

## Project Highlights 🚀
- **Goal**: Build a machine learning model to predict if it’s going to rain the next day.
- **Models Used**: Trained five different models to figure out which one works best for rainfall predictions.
- **Dataset**: Weather data including temperature, wind speed, humidity, and daily rainfall across Australia.

## Project Breakdown 🔍

### 1. Data Preprocessing
- Loaded the weather data and cleaned it up (goodbye missing values!).
- Transformed categorical features and standardised numerical ones to make sure everything is on the same page.

### 2. Exploratory Data Analysis (EDA)
- Played around with the data, visualizing trends and correlations to uncover weather patterns that could influence rainfall.

### 3. Model Training
Trained and evaluated five different machine learning models:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost
- LightGBM

I looked at metrics like accuracy, precision, and recall to decide how well each model performed.

### 4. Model Comparison & Results
- Spoiler alert: LightGBM came out on top! It had the best accuracy and a nice balance between precision and recall.

 ## What I Learned 📚
- **Data Cleaning & Preprocessing**: I got really comfortable with cleaning datasets, handling missing values, and transforming data to make it model-ready.
- **Exploratory Data Analysis (EDA)**: I learned how to visualise and explore weather trends to make informed predictions.
- **Model Comparison**: I got hands-on experience comparing different models based on various evaluation metrics, which helped me understand their strengths and weaknesses.

## What I Used 🛠️
- **Libraries**: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, LightGBM, XGBoost
- **Tools**: Jupyter Notebook for coding and visualizations

## What Went Well 🌟
- **LightGBM’s Performance**: LightGBM turned out to be the rockstar, delivering high accuracy and a solid balance between precision and recall.
- **Data Visualization**: The visualizations helped me uncover patterns in the weather data that guided model selection.

## What Went Poorly 💥
- **Handling Missing Values**: Some parts of the dataset had more missing values than I anticipated, and though I handled them, it took longer than expected to clean the data properly.
- **Model Training Time**: Some models (especially Random Forest and XGBoost) took a bit too long to train due to the large dataset. I had to optimise them for better performance.

## Final Thoughts 🤔
This project taught me a lot about machine learning workflows, from data cleaning to model evaluation. It also showed me how important it is to choose the right model for the job. Looking forward to exploring more weather prediction models and applying this experience to future projects!
