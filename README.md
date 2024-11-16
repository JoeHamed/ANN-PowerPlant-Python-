## ANN for Regression with TensorFlow and Keras
- This project demonstrates the development of an Artificial Neural Network (**ANN**) to predict a target variable based on multiple features using TensorFlow and Keras. The dataset (**_Folds5x2_pp.xlsx_**) contains features such as temperature, pressure, and humidity, with the target variable representing energy output.

1. **Data Preprocessing**: The dataset is loaded, and features (**X**) and target values (**y**) are extracted. The data is split into training and test sets using an **80-20** split.
2. **Building the ANN**:
   The ANN consists of an input layer, **two** hidden layers with **3** neurons each using **_ReLU_** activation, and an output layer for regression.
3. **Training the Model**: The ANN is compiled using the Adam optimizer and Mean Squared Error as the loss function. The model is trained over **100** epochs with a batch size of **32**.
4. **Prediction**: After training, the model predicts the test set values and the predictions are compared with actual values for evaluation.
