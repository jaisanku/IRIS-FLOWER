# IRIS-FLOWER
To develop a model that classifies iris flowers into their respective species based on sepal and petal measurements using the Iris dataset, follow the steps below. This implementation will use the Logistic Regression model to classify the flowers into one of the three species: setosa, versicolor, and virginica.
Loading the Dataset:The Iris dataset is loaded from a CSV file into a pandas DataFrame.
Exploring the Data:Basic exploration is conducted to understand the dataset, including checking the first few rows, data types, and summary statistics.
Preprocessing:The features (X) are separated from the target variable (y).
StandardScaler is used to normalize the features, which is particularly important for models like Logistic Regression.
Splitting the Data:The dataset is split into training and testing sets, with 20% of the data reserved for testing.
Training the Model:Logistic Regression is chosen as the classification model and trained on the training data.
Making Predictions:The model is used to predict the species of iris flowers in the test set.
Evaluating the Model:The model’s performance is evaluated using accuracy, a classification report, and a confusion matrix.
Prediction on New Data:The model is tested with a new sample of iris flower measurements to predict the species.
