# deep-learning-challenge

## Table of contents

* [Overview](#Overview)
* [Data Preprocessing](#Data-Preprocessing)
* [Model Architecture](#Model-Architecture)
* [Performance](#Performance)
* [Questions](#Questions)
* [References](#References)

## Overview

This challenge contains a deep learning model developed to analyze and predict the success of funding applications for Alphabet Soup, a charity organization. The challenge focuses on preprocessing the provided data, designing a neural network model, and evaluating its performance.

## Data Preprocessing

1. Removed non-beneficial columns (EIN, N``AME, STATUS, SPECIAL_CONSIDERATIONS, ASK_AMT). 
2. Encoded categorical data.
3. Standardized numerical features using StandardScaler.
4. Split the data into training and testing sets.

## Model Architecture

### The neural network model consists of:

1. **Input Layer:** Matches the number of features.
2. **Hidden Layers:**
    * **Layer 1:** ReLU activation with units based on hidden_nodes_layer1.
    * **Layer 2:** ReLU activation with units based on hidden_nodes_layer2.
3. **Output Layer:** Sigmoid activation for binary classification.

## Performance

* **First Attempt:** Accuracy of 72.37%.
* **Second Attempt:** Accuracy of 73.68%.
* **Third Attempt:**  Accuracy of 73.57%.

## Questions

In case of any additional questions please visit my GitHub link: [Feda](https://github.com/Feda2020)

## References

* Xpert Learning (https://bootcampspot.com)