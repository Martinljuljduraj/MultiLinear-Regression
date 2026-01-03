# MultiLinear-Regression

In this project, we are building a multi‑linear regression model that predicts the price of a house based on three input features: size, number of bedrooms, and age. We begin by preparing our dataset and normalizing the values so that each feature is on a similar scale. This prevents any single feature, such as size, from overpowering the others during training. After that, we initialize our model parameters which are three weights and one bias. These will be adjusted as the model learns from the data.

Once the setup is complete, we run the model through a training loop where it repeatedly makes predictions, calculates the error, and updates its parameters using gradient descent. Over many iterations, the model gradually improves its predictions and reduces the loss. After training finishes, we display the final learned weights and bias, which show how each feature contributes to the predicted house price.
