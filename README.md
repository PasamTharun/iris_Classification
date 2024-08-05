# 🌸 Iris Classification

This project showcases machine learning techniques to classify the Iris dataset. We utilize both a Random Forest Classifier and a Neural Network to predict the species of iris flowers based on their features.

🚀 Getting Started
<br>
Dependencies:
<br>
Ensure you have the following libraries installed to run the code:

          ->numpy
          ->pandas
          ->scikit-learn
          ->matplotlib
          ->seaborn
          ->tensorflow
You can install these libraries using pip:
pip install numpy pandas scikit-learn matplotlib seaborn tensorflow

📊 Data Loading and Preparation
<br>
Load the Iris dataset: Use scikit-learn’s load_iris function.
<br>
Create a DataFrame: Convert the data into a pandas DataFrame for easy manipulation.
<br>
Split the data: Separate features from target labels.
<br>
Encode target labels: Convert labels into numerical format using LabelEncoder.
<br>
Train-Test Split: Divide the data into training and testing sets (80-20 ratio).
<br>
🌲 Random Forest Classifier
Initialize and Train: Train a Random Forest Classifier with 100 estimators on the training data.
<br>
Evaluate the Model: Assess the model’s performance using accuracy, classification report, and confusion matrix.
<br>
Visualize Results: Create visualizations for accuracy, classification report, and confusion matrix using matplotlib and seaborn.

Results
Accuracy: 0.97
Classification Report:

![image](https://github.com/user-attachments/assets/72e0174e-58ee-43da-b7f6-0b4a5ace010c)
<br>

Confusion Matrix:



#🤖 Neural Network
Normalize Features: Apply StandardScaler to normalize the data.
Build and Train: Construct and train a neural network with one hidden layer.
Evaluate the Model: Measure the model’s accuracy on the test set.

Results
Accuracy: 0.98
Accuracy Plot:

#📈 Additional Metrics
F1 Score: 0.96
Precision Score: 0.97
Recall Score: 0.95

🔍 Correlation Matrix
Visualize feature relationships with the correlation matrix.


🏆 Conclusion
This project demonstrates the effectiveness of both the Random Forest Classifier and Neural Network in classifying the Iris dataset. Both models achieve high accuracy, supported by detailed metrics and visualizations.

