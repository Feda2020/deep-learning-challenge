# Report on the Performance of the Deep Learning Model for Alphabet Soup

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate a deep learning model to predict outcomes for Alphabet Soup, a charity organization. The goal was to determine whether applicants would be successful if funded, based on historical data. The analysis involved data preprocessing, model training, and evaluation to achieve optimal performance.

## Results

### Data Preprocessing

* **Target Variable:** The dependent variable represented applicant success.

* **Features:** Key features were retained after preprocessing, excluding non-beneficial columns. The features likely included numerical and categorical variables relevant to the prediction task.

* **Removed Variables:** The columns EIN, NAME, STATUS, SPECIAL_CONSIDERATIONS, and ASK_AMT were excluded as they were deemed non-beneficial for training.

### Compiling, Training, and Evaluating the Model

* **The neural network included three layers:**

    1. **First Hidden Layer:** Number of neurons defined by hidden_nodes_layer1 with a ReLU activation function.

    2. **Second Hidden Layer:** Number of neurons defined by hidden_nodes_layer2 with a ReLU activation function.

    3. **Output Layer:** A single neuron with a sigmoid activation function for binary classification.

* **Model Performance:**

    1. **First Attempt:** Achieved an accuracy of 72.37%.

    2. **Second Attempt:** Achieved an accuracy of 73.68%.

    3. **Third Attempt:** Achieved an accuracy of 73.57%.

* **Steps Taken to Improve Performance:**

    1. Adjusted the number of neurons in the hidden layers.

    2. Tuned the activation functions and optimization parameters.

    3. Experimented with additional preprocessing, including replacing rare categories with an "Other" label to reduce noise.

## Summary

The deep learning model achieved a maximum accuracy of 73.68%, even though it was slightly improved, but may fall short of a desired performance for reliable predictions. 
Overall, the deep learning model was around 73% accuracy in predicting the classification problem. 
Using a model with greater correlation between input and output would likely result in higher prediction accuracy. Better prediction can be achieved by doing additional data cleanning, and using a model with different activation functions and iterating until higher accuracy is reached.