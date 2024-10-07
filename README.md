# Drug Classification with Machine Learning

![](https://eos.org/wp-content/uploads/2023/01/pills-in-hand.jpg)

This project demonstrates a drug classification problem using various machine learning techniques. The following key machine learning concepts and libraries are covered:

- **Pandas**: Used for data manipulation and analysis.
- **DecisionTreeClassifier**: A supervised learning algorithm for classification tasks.
- **KNeighborsClassifier**: Another supervised learning method that classifies based on the 'k' nearest neighbors.
- **OneHotEncoder**: Transforms categorical variables into binary form.
- **Matplotlib-Pyplot**: A plotting library for creating visualizations.
- **ColumnTransformer**: Allows multiple preprocessing steps to be applied on specific columns.
- **Train-Test-Split**: A method to split the dataset into training and testing sets.
- **sklearn-tree**: Part of scikit-learn for decision tree models.
- **sklearn-model**: Scikit-learn's interface for model training and testing.
- **sklearn-preprocessing**: Tools for preprocessing data (e.g., normalization, encoding).
- **sklearn-compose**: A module to streamline column transformations.

## Dataset

We use a drug classification dataset which contains information about patients and drugs prescribed to them. The dataset can be found at the following link:

- [Drug Classification Dataset](https://www.kaggle.com/datasets/prathamtripathi/drug-classification)

The data includes attributes such as age, sex, blood pressure levels, cholesterol levels, and the drug prescribed.

## Notebook

The notebook used to implement the solution for this project is available on Kaggle and demonstrates how to load, preprocess, and build machine learning models to classify drugs.

- [Drug Classification Notebook](https://www.kaggle.com/code/ahmadsaadaldeen/ml-drug-classification/notebook)

## Methodology

The process for this project involves the following steps:

1. **Data Preprocessing**: 
   - Using `Pandas` to explore and clean the dataset.
   - Encoding categorical variables with `OneHotEncoder`.
   - Splitting the dataset into training and testing sets using `train_test_split`.

2. **Model Building**:
   - Implementing decision tree and k-nearest neighbor classifiers using `DecisionTreeClassifier` and `KNeighborsClassifier` from `scikit-learn`.
   - Using `ColumnTransformer` to handle different data preprocessing steps for numerical and categorical features.
   
3. **Model Evaluation**:
   - Assessing the models' performance with accuracy and other metrics.
   - Visualizing results using `matplotlib-pyplot`.

## Libraries

To run this project, the following Python libraries are required:

- `pandas`
- `scikit-learn`
- `matplotlib`

