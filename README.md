# NN-from-scratch-Concrete-Strength

## Overview ##
This project implements a regression model to predict concrete strength using two approaches: a scratch implementation of linear regression and a library-based implementation using Keras. The primary goal is to understand the fundamentals of regression, gradient descent, and the effects of regularization while comparing performance between the two methods.

## Dataset ##
The dataset used in this project is the Concrete Strength Dataset, which includes various features related to the composition of concrete and the target variable representing its strength.

## Scratch Implementation ##
The scratch implementation includes:
- Custom scaler for feature normalization.
- Gradient descent algorithm for training the regression model.
- Evaluation metrics such as Mean Squared Error (MSE) and R² score.

## Key Insights ##
The scratch implementation performs reasonably well with an R² score of 0.8602 and an MSE of 36.0192.
This performance is notable considering the small size of the dataset, which allows for effective learning without overfitting.

## Keras Implementation ##
The Keras implementation utilizes a simple neural network architecture:
- One hidden layer with ReLU activation.
- Output layer for regression tasks.

## Performance Comparison ##
Scratch Model - MSE: 36.0192, R²: 0.8602, Time: 0.14 seconds
Keras Model   - MSE: 36.6451, R²: 0.8578, Time: 11.68 seconds

## Conclusions ##
This project looks at the basics of regression analysis and machine learning. By comparing my scratch implementation with a library method, I’ve learned the value of understanding algorithms from the ground up. The scratch model does well with the small dataset, but using libraries like Keras is important for scaling and handling more complex models in larger datasets. This experience has helped me see the strengths of both approaches!

## License ##
This project is licensed under the Apache License 2.0.
