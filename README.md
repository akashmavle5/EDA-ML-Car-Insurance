# EDA and Machine Learning - Car Insurance Claim Data

This is a project in which I use _Car Insurance Claim_ Dataset from Kaggle to generate some insights about car insurance claims and see what factors will make customers more likely to be 'repeat offenders'. First, I clean the data and create some new features using pandas. Then I create visualizations of said data using matplotlib and seaborn. Finally, I apply machine learning models (sklearn) to predict which customers will make repeat insurance claims. Tasks include:

### Data Cleaning and Feature Engineering:
- Create target variable 'repeat'
- Convert data types to numeric 
- Remove unnecessary columns
- Fill in and/or remove null values
- Clean up messy string data entries
- Export cleaned csv file

### Data Visualization:
- Create visualizations to determine what attributes lead to repeat insurance claims
- Make use of matplotlib and seaborn to create graphs that are easy to understand
- Separate numerical variables into categorical data for plotting
- Use visualizations to determine whether or not a variable is suitable for our ML model

### Machine Learning Models:
- Create target variable and feature dataframe
- Convert categorical data types to numeric
- Split dataset into training and test data
- Run different categorical machine learning models: 
    - Gaussian Naive Bayes
    - Logistic Regression
    - Support Vector Machines
    - Decision Tree
    - Random Forest
    - k-Nearest Neighbors
    - Gradient Boosting Classifier
- Measure accuracy of each model using sklearn.metrics.accuracy_score
- Run various tests to determine best model
