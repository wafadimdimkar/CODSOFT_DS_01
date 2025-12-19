# CODSOFT_DS_01
📊 Task 1: Data Cleaning & Preprocessing using Python<br>
📌 Project Overview<br>

This project focuses on cleaning and preprocessing a raw movie dataset using Python.<br>
The dataset contains missing values, inconsistent formats, and categorical data that must be processed before applying any machine learning model.<br>

The objective of this task is to prepare a clean, machine-learning-ready dataset by handling missing values, correcting data types, and encoding categorical features.<br>

🎯 Objective<br>

Identify and handle missing values<br>

Convert non-numeric data into numeric format<br>

Clean inconsistent columns such as duration and votes<br>

Encode categorical features for ML models<br>

Prepare the dataset for model training<br>

🛠️ Tools & Libraries Used<br>

Python<br>

Pandas<br>

NumPy<br>

Jupyter Notebook<br>

📂 Dataset Description<br>

The dataset includes movie-related attributes such as:<br>

Year – Release year of the movie<br>

Duration – Movie length in minutes<br>

Genre – Movie genre<br>

Votes – Number of IMDb votes<br>

Director – Movie director<br>

Actor 1, Actor 2, Actor 3 – Leading actors<br>

Rating – IMDb movie rating (target variable)<br>

🔧 Data Cleaning Steps Performed<br>
1️⃣ Handling Missing Values
<br>
Identified missing values using .isnull().sum()<br>

Filled numerical columns using median<br>

Filled categorical columns using mode<br>

2️⃣ Cleaning Duration Column
<br>
Removed non-numeric characters<br>

Converted values to integers<br>

3️⃣ Cleaning Votes Column<br>

Removed commas (e.g., 17,774 → 17774)<br>

Converted values to numeric format<br>

4️⃣ Encoding Categorical Columns<br>

Applied Label Encoding to:<br>

Genre<br>

Director<br>

Actor 1, Actor 2, Actor 3<br>

5️⃣ Final Dataset Validation<br>

Verified data types<br>

Ensured no missing values<br>

Confirmed dataset readiness for ML models



Dataset ready for machine learning training

