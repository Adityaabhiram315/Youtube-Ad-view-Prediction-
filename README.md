# Youtube-Ad-view-Prediction-

![image](https://github.com/Adityaabhiram315/Youtube-Ad-view-Prediction-/assets/95640107/e0c020d1-7c52-4fa8-aaec-164aa7437c58)

### Introduction
The YouTube AdView Prediction project aims to construct a machine learning model capable of forecasting YouTube adview counts based on various YouTube metrics. The project involves analyzing data such as views, likes, dislikes, comments, publication date, duration, and category to predict adview counts.

### Table of Contents
Introduction
Installation & Library Imports
Data Loading
Exploratory Data Analysis
Feature Engineering
Model Development
Prediction Generation

1. Introduction
Run the below cell if the required libraries are not installed previously.

2. Installation & Library Imports
Install and import the necessary libraries, including "missingno" for visualizing missing values and "optuna" for hyperparameter tuning.

3. Data Loading
Load the train and test datasets, i.e., "train.csv" and "test.csv," containing details of approximately 15,000 YouTube videos.

4. Exploratory Data Analysis
Explore the first 5 rows, data shape, information, data types, and null values in the train and test datasets.

5. Feature Engineering
Perform feature engineering tasks such as handling missing data, feature scaling, and data transformation.

6. Model Development
Utilize machine learning models such as XGBRegressor, LGBMRegressor, Ridge, Lasso, RandomForestRegressor, GradientBoostingRegressor, SVR, and StackingRegressor for predicting adview counts.

7. Prediction Generation
Generate predictions using the developed machine learning models.

### Code Files
The main code file can be accessed from the following link: youtube_adview_prediction_ML-INTERNSHIP.ipynb

### Additional Information:

Train Data Analysis:

Statistical Analysis: The train dataset consists of details such as views, likes, dislikes, comments, and adview counts for about 15,000 YouTube videos. Statistical analysis provides insights into the distribution of these metrics.
Data Type: The train dataset contains a mix of object and integer data types, with 8 columns as objects and 1 column as an integer.
Test Data Exploration:

First 5 Rows: Display the first 5 rows of the test dataset showcasing a glimpse of the data structure.
Data Shape: The test dataset has 8764 rows and 8 columns, providing information on the dimensionality of the dataset.
Data Type: Exploring the data types in the test dataset reveals that all columns are categorized as objects.
Data Columns and Characteristics:

The data columns in both the train and test datasets include essential information such as "vidid," "views," "likes," "dislikes," "comment," "published," "duration," and "category."
The data types for the columns are primarily objects, indicating categorical or text data.
Null Data Analysis in Test Data:

The examination of null data in the test dataset shows that there are no missing values in any of the columns.
The absence of null data in the test dataset ensures data completeness for analysis and model building.

### Conclusion
The project by Aditya Abhiram aims to showcase the use of machine learning techniques for predicting YouTube adview counts. The code and documentation provide insights into data analysis, model development, and prediction generation.




