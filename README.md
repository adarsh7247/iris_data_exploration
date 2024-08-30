# iris_data_exploration
Iris Dataset Exploration

Step 1: Import Necessary Libraries

- Import the required libraries:
    - pandas for data manipulation and analysis
    - load_iris from scikit-learn for loading the Iris dataset

Code:

import pandas as pd
from sklearn.datasets import load_iris


Step 2: Load the Iris Dataset

- Load the Iris dataset using load_iris
- Convert the dataset into a Pandas DataFrame iris_df with feature names as columns

Code:

iris = load_iris()
iris_df = pd.DataFrame(data=iris.data, columns=iris.feature_names)


Step 3: Display the First Five Rows

- Print the first five rows of the dataset using head()

Code:

print("First five rows of the dataset:")
print(iris_df.head())


Step 4: Display the Shape of the Dataset

- Print the shape of the dataset (number of rows and columns) using shape

Code:

print("\nShape of the dataset:")
print(iris_df.shape)


Step 5: Display Summary Statistics

- Print summary statistics (mean, std, min, 25%, 50%, 75%, max) for each feature using describe()

Code:

print("\nSummary statistics of the dataset:")
print(iris_df.describe())

