# 🌸 Iris Classification

This project showcases machine learning techniques to classify the Iris dataset. We utilize both a Random Forest Classifier and a Neural Network to predict the species of iris flowers based on their features.

<h2>🚀Getting Started</h2>
<b>Dependencies:</b>
Ensure you have the following libraries installed to run the code:

          ->numpy
          ->pandas
          ->scikit-learn
          ->matplotlib
          ->seaborn
          ->tensorflow
<br>          
You can install these libraries using pip:

```bash
   pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
```
<h2>📊Data Loading and Preparation</h2>
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
<h2>🌲Random Forest Classifier</h2>
Initialize and Train:-Train a Random Forest Classifier with 100 estimators on the training data.
<br>
Evaluate the Model:-Assess the model’s performance using accuracy, classification report, and confusion matrix.
<br>
<h2>📈Visualize Results:</h2>
Create visualizations for accuracy, classification report, and confusion matrix using matplotlib and seaborn.
<br>
<h2>🎯Classification Report:</h2>

![image](https://github.com/user-attachments/assets/72e0174e-58ee-43da-b7f6-0b4a5ace010c)

<h2>Confusion Matrix:</h2>

![image](https://github.com/user-attachments/assets/fa2bc18c-6a68-4579-a05e-dba22c52bcfd)
<br>
<h2>🤖Neural Network</h2>

Normalize Features:-Apply StandardScaler to normalize the data.
<br>
Build and Train:-Construct and train a neural network with one hidden layer.
<br>
Evaluate the Model:-Measure the model’s accuracy on the test set.
<br>
<b>Results</b>
<br>
Accuracy:-100%
<br>
<b>Accuracy Plot Of Neural Networks:</b>
<br>

![image](https://github.com/user-attachments/assets/9e42efc2-f16c-4a87-b990-2a1f27655bc1)
<h2>🔍 Correlation Matrix:-</h2>
Visualize feature relationships with the correlation matrix.

![image](https://github.com/user-attachments/assets/c53243c9-c01f-4e2a-b612-b7217092329e)
<br>
<h2>🏆Conclusion</h2>

This project demonstrates the effectiveness of both the Random Forest Classifier and Neural Network in classifying the Iris dataset. Both models achieve high accuracy, supported by detailed metrics and visualizations.

