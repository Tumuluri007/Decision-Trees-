Decision Trees and Random Forests in Machine Learning
This repository contains a project that demonstrates the use of Decision Trees and Random Forests for predicting hiring outcomes based on a dataset of past hires. The project is implemented in Python using libraries such as Pandas, NumPy, scikit-learn, and pydotplus for data handling, machine learning, and visualization.

Files
PastHires.csv: Contains the dataset of past hires with features like Years of Experience, Employment Status, Previous Employers, Level of Education, Top-tier School, Internship, and the Hiring Decision.
Project Description
1. Data Loading and Preprocessing
We begin by loading the dataset using Pandas and converting categorical data to numerical values. This is essential because scikit-learn's decision tree classifier requires numerical input. The categorical mappings are as follows:

'Y' -> 1, 'N' -> 0 for binary features.
'BS' -> 0, 'MS' -> 1, 'PhD' -> 2 for levels of education.

2. Feature Selection
The features for the decision tree are selected from the dataset. The target variable is the 'Hired' column.

3. Building the Decision Tree
We create a decision tree classifier using scikit-learn and fit it to the dataset.

4. Visualizing the Decision Tree
To visualize the decision tree, we use the pydotplus library to generate a PNG image.

5. Ensemble Learning with Random Forest
We use a Random Forest classifier with 10 decision trees to improve prediction accuracy. Random Forests combine the output of multiple decision trees to make a final prediction.

Key Points
Data Preprocessing: Conversion of categorical data to numerical values is crucial.
Model Building: Decision Tree and Random Forest classifiers are used for prediction.
Visualization: The decision tree is visualized to understand the decision-making process.
Ensemble Learning: Random Forest enhances prediction accuracy by combining multiple decision trees.
Requirements
pandas
numpy
scikit-learn
pydotplus
IPython
How to Run
Install the required libraries: pip install pandas numpy scikit-learn pydotplus
Load the data and run the preprocessing steps.
Build and visualize the decision tree.
Use the Random Forest classifier to make predictions.
