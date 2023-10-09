# Breast-Cancer-Classification-Using-Neural-Network
## Task
Build a Machine Learning Model to Predict whether the Breast Cancer is Malignent or Benign using Neural Network Techniques.</br>
Tool Used: Jupyter Notebook, Python
## Steps Involved
### Import Dependencies
- Numpy
- Pandas
- Matplotlib
- Train_test_split
- Standard Scaler
- Tensorflow
- Keras
### Data Collection and Processing
- Load the data from sklearn datasets
- Laod the data into Pandas DataFrame
- Use function shape, Describe, isnull, info and value_counts to understand the data
- Split the dataframe into features and Target
- Split the whole dataframe into training and test data
- Standardize the X_train and X_test data
### Building the Neural Network
- Setting up the layers of Neural Networks
  - 1 input layer with flatten function
  - 2 hidden layer of 20 nodes with Dense function and 'relu' activation
  - 1 output layer of 2 nodes(2 classes) with dense function and 'sigmoid' activation
- Compile the Neural Network
- Train the model with training data with a validation split of 10%
- Plot the graph represting model loss and accuracy for both training data and validation data
- Calculate the accuracy of the model on the test data
  - Accuracy of test data:  97.37
### Build a Predictive System
- Get a random input from the dataset
- Change the input to numpy array
- Reshape the array to 2 Dimension Array
- Standardize he data
- Feed the data to the build model
- Predict function will give the result in array with the length of number of classes each represent the probility of being in that particular class
- Use argmax function of numpy to get the position with highest probability
- Print the result
