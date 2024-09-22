

# SGD Linear Regression - Boston Housing Dataset

This project implements **Stochastic Gradient Descent (SGD)** for linear regression on the Boston Housing dataset. The aim is to predict house prices using both a custom SGD implementation and scikit-learn's SGDRegressor.

## Dataset
- **Boston Housing Dataset**:
  - 506 instances with 13 features related to housing characteristics.
  - Target variable: Median house price in $1000's.

## Key Features
- **Custom SGD Implementation**:
  - Developed from scratch to perform linear regression using gradient descent.
  - Implemented key parameters: learning rate, iterations, shuffle, and divide for learning rate decay.

- **scikit-learn SGDRegressor**:
  - Compared the performance of the custom SGD with scikit-learn's built-in SGDRegressor.
  
## Results
- **Mean Squared Error (MSE)**:
  - Custom SGD (Trial 1): MSE = 8.9e+24 (poor performance due to initial parameter tuning).
  - Custom SGD (Trial 2): MSE = 22.5 (close to scikit-learn's results after parameter optimization).
  - scikit-learn SGD: MSE = 22.2.
  - scikit-learn Linear Regression: MSE = 22.1.

## Conclusion
The custom SGD implementation achieves similar performance to scikit-learn's SGDRegressor when properly tuned. It highlights the importance of learning rate, iterations, and parameter optimization in SGD.
