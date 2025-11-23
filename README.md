# Applied Data Science Capstone - SpaceX Landing Prediction

## Project Overview
This repository contains the capstone project for the **IBM Applied Data Science Specialization** on Coursera. The goal of this project is to predict whether the Falcon 9 first stage will land successfully.

SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company ("Space Y") wants to bid against SpaceX for a rocket launch.

## Project Structure & Methodology
The project follows the standard Data Science methodology:

1.  **Data Collection:**
    * Using SpaceX REST API.
    * Web Scraping from Wikipedia using BeautifulSoup.
2.  **Data Wrangling (Pre-processing):**
    * Filtering data for Falcon 9 launches.
    * Handling missing values (Mean imputation).
    * One-Hot Encoding for categorical variables.
3.  **Exploratory Data Analysis (EDA):**
    * Using SQL to query the dataset.
    * Visualizing success rates and payload mass distributions using Matplotlib & Seaborn.
4.  **Interactive Visual Analytics:**
    * **Folium:** Interactive maps to visualize launch sites and success clusters.
    * **Plotly Dash:** Built a dashboard to filter launches by site and payload range.
5.  **Predictive Analysis (Machine Learning):**
    * Built and compared 4 classification models:
        * Logistic Regression
        * Support Vector Machine (SVM)
        * Decision Tree
        * K-Nearest Neighbors (KNN)
    * Hyperparameter tuning using GridSearchCV.

## Technologies Used
* **Python 3**
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium, Plotly, Dash
* **API:** SpaceX REST API
* **Database:** SQL (Db2 or SQLite)

## Key Findings
* Identified that launch success rates have improved significantly over time.
* Launch sites like KSC LC-39A and CCAFS SLC-40 have higher traffic.
* Payload mass and orbit type are significant factors in landing success.
* The [Insert Best Model Name here, e.g., Decision Tree] model performed best with an accuracy of [Insert Accuracy]%.

## Certificate
This project was completed as part of the **IBM Applied Data Science Professional Certificate**.
