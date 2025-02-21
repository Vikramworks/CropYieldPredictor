Title :

Predicting Crop Production Based on Agricultural Data

Description :

This project aims to analyze, visualize, and predict crop production using agricultural datasets. By leveraging SQL for data extraction, Pandas for preprocessing, Streamlit for interactive dashboards, and Machine Learning for predictive modeling, this project provides insights into agricultural trends and future production estimates.

Key Components:

✅ Data Cleaning & Preprocessing: Handling missing values, outlier detection, and feature engineering.
✅ Exploratory Data Analysis (EDA): Identifying patterns, trends, and relationships between crop production, harvested area, and yield.
✅ Data Visualization: Using Matplotlib, Seaborn, and Streamlit to create interactive charts and heatmaps.
✅ SQL Integration: Querying structured agricultural data for efficient data retrieval and manipulation.
✅ Machine Learning (Regression): Training predictive models (Random Forest, Linear Regression) to estimate future crop production.
✅ Streamlit Dashboard: Building a user-friendly app for dynamic data filtering, model predictions, and insightful visualizations.

This project is a powerful blend of data science and web-based analytics, helping stakeholders make informed decisions about agriculture and food security. 🌱📈🚀
** Installation**

1.python 
   
2.Sql

*CREATE DATABASE agriculture_data;

3.pip install virtualenv

4.python -m venv crop_env    

5.pip install pandas  

6.pip install numpy  

7.pip install matplotlib  

8.pip install seaborn  

9.pip install scikit-learn  

10.pip install sqlalchemy  

11.pip install pymysql  

12.pip install streamlit  

13.pip install mysql-connector-python  
## Features

- Intractive
- Live prediction
- Live Insights 
- Explore Data


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`You Need Data`
`I share you the data file in my documentation`
##Lessons Learned

What did you learn while building this project? What challenges did you face, and how did you overcome them?

1.`First, understand the data – Before doing any processing, take time to analyze and explore the dataset.`

2.`Data Cleaning` – Remove inconsistencies, handle missing values, and ensure data quality.
Identify necessary features – While cleaning, determine which columns are essential for the analysis.

3.`Visualizing Data` – Use Matplotlib and Seaborn to gain insights through graphical representation.
Handling Outliers – Identify and treat outliers to avoid misleading results.

4.`Building a Model` – Once the data is processed, train a machine learning model to make predictions.


##Challenges Faced :


1.`Filtering Outliers` – Outliers can significantly impact model accuracy, so handling them properly is crucial.

2.Choosing the right method for outliers – Deciding whether to delete or cap the outliers can be challenging.

3.`Data Cleaning Complexity` – Dealing with missing values, incorrect entries, and inconsistencies takes time and effort.

4.`Outlier Treatment` – Instead of deleting data, capping outliers is preferred to avoid losing valuable information.

5.`Handling Spelling Mistakes & Inconsistencies – Correcting data entry errors ensures better model performance.`
## Roadmap

- Additional browser support

- Add more integrations

## Step--By--Step--Process

`Step-1`:

Load the Data in Python(`Pandas`)

Then You do Cleaning 

Treate Outliers

And then choose the `Model`

`Evaluate`

Then use Streamlit `or` Power BI to Display 
## Usage/Examples

```import pandas as pd

```df_capped = final_filtered_data.dropna(subset=['production', 'year', 'area_harvested', 'yield'])
                X = df_capped.drop(columns=["production"])
                Y = df_capped["production"]

                # One-hot encoding for categorical variables
                X = pd.get_dummies(X, columns=["area", "item"], drop_first=True)

                # Train-Test Split
                X_train, X_test, y_train, y_test = train_test_split(X, Y, test_size=0.2, random_state=42)```
## Screenshots

1.
 
![Screenshot 2025-02-21 180349](https://github.com/user-attachments/assets/b9b0d144-b3a6-4bba-93a4-2b459c9a62d5)

2.

![Screenshot 2025-02-21 180349](https://github.com/user-attachments/assets/31355a73-d0c1-43b9-a3c6-b40843b54231)

3.

![Screenshot 2025-02-21 180410](https://github.com/user-attachments/assets/5d1c8e63-ede4-4caf-9fb6-75cbb9f2c0d8)

4.

![Screenshot 2025-02-21 184547](https://github.com/user-attachments/assets/f30dde0d-9f5a-4337-b330-148eb4d2e2ae)

5.

![Screenshot 2025-02-21 184702](https://githubcom/user-attachments/assets/d15dafa0-0be6-4f17-8629-26e3c7002c11)

6.

![Screenshot 2025-02-21 184751](https://github.com/user-attachments/assets/02ced420-8b41-4a21-b500-bd8820dd62ad)

7.

![Screenshot 2025-02-21 184839](https://github.com/user-attachments/assets/c1bbf8d1-d191-4c30-8096-1a55bffb36cb)

## Demo Video : 

1. 

https://github.com/user-attachments/assets/4ea2aeca-996d-4d00-a70a-d0b95c0faf3a

2.

https://github.com/user-attachments/assets/9549d922-a73c-409c-aeb6-8d8d980ed15b

3.

https://github.com/user-attachments/assets/5c891cdb-93e4-471b-b4f0-1e308b6d6a4b


