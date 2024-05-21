## Diagnosis-of-diabetes

This code creates a predictive model for diagnosing diabetes based on patient data. First, the data related to diabetes is read from a CSV file and then it is divided into two parts, training and testing. Then the input and output data are determined for training and testing.

Then, the input data is scaled to give the best performance in the neural network. This operation is done using `StandardScaler`.

Then the data is displayed in a transformed form in different graphs. First, a box plot is drawn to show the distribution of variables, and then a scatter diagram is drawn for two variables, Glucose and Blood Pressure.

Then a neural network model is created using TensorFlow and Keras library. This model includes three layers with different activation functions: two layers with ReLU activation and one output layer with sigmoid activation to predict two categories of diabetes and non-diabetes.

After creating the model, it trains it and records the training accuracy in each training round (epoch). Then it calculates and prints the prediction accuracy of the model on the test data.

Finally, it saves the trained model for later use, also saves the model in `h5` and `tf` formats, ready to be loaded and used in other environments.

Data: https://www.kaggle.com/datasets/saurabh00007/diabetescsv
