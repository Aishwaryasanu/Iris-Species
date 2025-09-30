# Iris-Species
# K-Nearest Neighbors (KNN) Classification – Iris Dataset

This project demonstrates how to implement K-Nearest Neighbors (KNN) classification on the Iris dataset using Python.
It includes data preprocessing, exploratory analysis, model training, hyperparameter tuning, evaluation, and visualization.

Project Objectives
1. Choose a classification dataset and normalize features
2. Use KNeighborsClassifier from scikit-learn
3. Experiment with different values of K
4. Evaluate the model using accuracy and confusion matrix
5. Visualize decision boundaries to understand how KNN separates classes

Dataset
The dataset used is Iris.csv.
It contains 150 samples of iris flowers with the following features:
* SepalLengthCm
* SepalWidthCm
* PetalLengthCm
* PetalWidthCm

The target variable is Species with three possible classes: Setosa, Versicolor, and Virginica.

Tools and Libraries
* Python 3.10 or higher
* Pandas for data handling
* NumPy for numerical operations
* Matplotlib for visualization
* Seaborn for statistical plots
* Scikit-learn for machine learning models and evaluation metrics

Steps Implemented

1. Data Loading and Cleaning
   * Loaded the Iris dataset from CSV
   * Dropped the Id column as it is not useful for classification

2. Exploratory Data Analysis (EDA)
   * Checked dataset shape, info, and class distribution
   * Created pairplots and feature distribution plots to understand separation of classes

3. Feature Scaling
   * Standardized all features using StandardScaler to ensure fair distance measurement for KNN

4. Train/Test Split
   * Split dataset into 70 percent training data and 30 percent testing data

5. Model Training and Hyperparameter Tuning
   * Trained KNeighborsClassifier with different values of K (1 to 20)
   * Plotted accuracy against K to determine the best value

6. Evaluation
   * Calculated accuracy score on the test set
   * Generated confusion matrix and displayed it as a heatmap
   * Produced classification report with precision, recall, and F1-score

7. Visualization
   * Visualized KNN decision boundary for Sepal Length vs Sepal Width feature pair

Results
* Best K value is usually around 5, depending on the random train-test split
* Model achieves very high accuracy (often above 95 percent)
* Decision boundaries clearly show separation among the three iris species

License
This project is open-source and available under the MIT License.


Do you also want me to prepare a `requirements.txt` file content that you can add to your repo so others can easily install all dependencies?
