# iris_Classification

This project demonstrates the use of machine learning techniques to classify the Iris dataset. We use both a Random Forest Classifier and a Neural Network to predict the species of iris flowers based on their features.

Dependencies
Ensure you have the following libraries installed to run the code:

            --numpy
            --pandas
            --scikit-learn
            --matplotlib
            --seaborn
            --tensorflow
Data Loading and Preparation

Load the Iris dataset:-The dataset is loaded using scikit-learn's load_iris function.

Create a DataFrame:-The data is converted into a pandas DataFrame for easier manipulation and analysis.

Split the data into features and target:-The features and target labels are separated.

Encode target labels:-The target labels are encoded using LabelEncoder to convert them into numerical format.

Split the data into training and testing sets:-The data is split into training and testing sets using an 80-20 ratio.
