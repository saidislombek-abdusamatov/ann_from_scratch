# ANN Classifier and Regressor

This project implements an Artificial Neural Network classifier and regressor for solving classification problems.

![img](https://149695847.v2.pressablecdn.com/wp-content/uploads/2018/12/nural-network-banner-1024x614.gif)

## About The Project

The ANN class creates an ANN model based on given input shape, number of layers and their parameters, and loss function. It has the following capabilities:

- Various activation functions (sigmoid, relu, tanh, softmax)
- Different loss functions (mean squared error, binary cross entropy, categorical cross entropy)
- Forward and backward propagation
- Model training and evaluation 
- Making predictions on test data

## Usage

To use the project, follow these steps:

1. Import required libraries:

```python
import numpy as np
```

2. Create an ANN model:

```python
model = ANN(input_shape, layers, loss_function)
``` 

3. Prepare training data:

```python
X_train, y_train = ... # numpy arrays  
```

4. Train the model: 

```python
model.fit(X_train, y_train, epochs, batch_size, ...)
```

5. Make predictions using the model:

```python
y_pred = model.predict(X_test)
```
