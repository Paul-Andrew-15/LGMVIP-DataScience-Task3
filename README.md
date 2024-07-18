# LGMVIP-DataScience-Task3
## Iris Species Classification using Decision Tree Algorithm
### Overview:
The objective of this project is to build a Decision Tree classifier to predict the species of iris flowers based on their physical characteristics. The dataset used for this project is the famous Iris dataset, which contains 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The target variable is the species of the iris flower, which can be one of three classes: Iris-setosa, Iris-versicolor, or Iris-virginica.

### Steps Involved:
1. Data Collection:
The dataset iris.csv contains the following columns: Id, SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, Species.
The dataset includes 150 samples of iris flowers, with 50 samples for each species.

2. Data Preprocessing:
Load the dataset using the pandas library.
Select the relevant features (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm) and the target variable (Species).
Split the dataset into training and testing sets to evaluate the model's performance.

3. Model Training:
Use the scikit-learn library to create a Decision Tree classifier.
Train the classifier using the training dataset.

5. Model Evaluation:
Evaluate the model's performance using the testing dataset.
Calculate accuracy and other relevant metrics.

7. Model Visualization:
Visualize the trained Decision Tree using the plot_tree function from the scikit-learn library.
The visualization will display the structure of the Decision Tree, including the decision nodes, feature splits, and class predictions.

6. Prediction:
Use the trained classifier to make predictions on new data.
The model should be able to predict the species of an iris flower based on its sepal and petal measurements.
