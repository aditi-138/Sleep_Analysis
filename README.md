# Sleep Deprivation & Cognitive Performance Analysis

## 📌 Project Overview

This project explores the relationship between sleep deprivation and cognitive performance using machine learning techniques. The dataset includes sleep patterns, cognitive task results, and lifestyle factors, providing insights into how sleep impacts attention, memory, and emotional regulation.

## 📂 Dataset Details

Filename: sleep_deprivation_dataset_detailed.csv
Taken from Kaggle 
Rows: 60 (Participants)

Columns: 14 (Sleep, cognitive performance, lifestyle variables)

## Key Features:

Sleep_Hours, Sleep_Quality_Score, Daytime_Sleepiness

Stroop_Task_Reaction_Time, N_Back_Accuracy, PVT_Reaction_Time

Age, Gender, BMI, Caffeine_Intake, Physical_Activity_Level, Stress_Level

## ⚡ Machine Learning Models Used

Linear Regression: Predicts cognitive performance based on sleep hours.

Random Forest Classifier: Classifies participants based on sleep deprivation severity.

## 🛠️ How to Run This Notebook

Upload the dataset to Google Colab:

from google.colab import files
uploaded = files.upload()

Load the dataset:

import pandas as pd
df = pd.read_csv("sleep_deprivation_dataset_detailed.csv")

Check column names to avoid errors:

print(df.columns)
df.columns = df.columns.str.strip()  # Removes extra spaces

Preprocess & Train ML Models (see notebook for details)

## 📌 Key Findings

Sleep deprivation significantly impacts reaction time and accuracy.

High stress levels and caffeine intake correlate with lower sleep quality.

Feature importance shows Sleep_Hours and PVT_Reaction_Time as key predictors.

## 🚀 Uploading to GitHub

Create a new repository on GitHub.

Clone the repository (if using local setup):

git clone https://github.com/your-username/sleep-deprivation-ml.git
cd sleep-deprivation-ml

Upload files:

git add .
git commit -m "Added dataset and notebook"
git push origin main

If using GitHub web, manually upload:

sleep_deprivation_dataset_detailed.csv

sleep_analysis.ipynb

README.md

## 📧 Contact

For questions or collaborations, reach out via GitHub Issues or email: aditighosh138@gmail.com
