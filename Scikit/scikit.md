## Scikit-learn

- sklearn is a powerful python libarary for building machine learning models.
- Loading the sample data
- Tools to Splitting the data for training/testing.
- Ready to use models like regression/classification, we don't need to write algoirthm from behind.
- Evaluating model accuracy

## Common Modules in sklearn like.

- **Datasets:** sklearn.datasets is the module, we can load_iris datasets or some other datasets.
- **Classification:** sklearn.linear_model, we can use logistic regression.
- **Regression:** sklearn.linear_model, we can use Linear regression.
- **Clustering:** sklearn.cluster, we can use KMeans().
- **Dimensionality :** sklearn.decomposition, we can use PCA.
- **Preprocessing:** sklearn.preprocessing, we can use  StandardScaler(), MinMaxScaler().
- **Model Selection:** sklearn.model_selection, we can use train_test_split() tools.
- **Evaluation Metrics:** sklearn.metrics for calculating the metrices..

## Load the sample data using sklearn, train and test the model using logistic regression which is classification.

## 1. Load the sample data

- Iris flowers dataset loads the flower data.This datasets has 4 features(columns) and 150 flowers(data).
- we can use sklearn.datasets to load the datasets.
- load the entire datasets in a variable called data.
        
    ![alt text](Images/loadSampleData.png)

## 2. Splitting the Features(X) and Labels(Y)

- Split the data into X and Y.
- X contains 2D arrays shape of(150,4) with 4 column and 150 rows(what is the length, width).
- Y contains flower names with specifying values..

    ![alt text](Images/splitting.png)

## 3. Train-Test Split

- Used to split the data into training and testing.
- you are splitting 80% of the data for training and 20% is for testing.
- X_train and Y_train is used to train the model.
- X_test and Y_test is used to test how well the model performs.
- use sklearn.model-selection to get the tool to split the data.
    
    ![alt text](Images/trainTest.png)

## 4. Build Model 

- This is our machine learning model for classification.
- create a Logistic regression model, this model is used to train the training data..
- The model learns how different features is relate to the flower type.
- .fit() makes the model learn from the training data.

![alt text](Images/model.png)

## 5. Evaluating the Model

- Load the Iris datasets from the sklearn datasets.
- Store the input values in X and output values in Y.
- use train_test_split() from model_selection, try to split the datasets like X_train, X_test, Y_train and Y_test,use 80% to training and 20% to splitting.
- we can classification from logistic regression to classify the model,Train the model with X_train and Y_train.
- The model predicates the flower name for the test set X_test save into a variable.
- And after that compares actual answer(y_test) with predicted ones(y_pred)
- For comparing use metrics module from the sklearn library it will return number like 0.96 which is 96% accurate.
- Classification reports provides  precision, recall and f1-score.

![alt text](Images/evaluate.png)
