# deep-learning-challenge



**Overview of the Analysis:**

The purpose of this analysis was to build a deep learning model for binary classification to predict whether applicants will be successful if funded by Alphabet Soup. The dataset was preprocessed, including one-hot encoding categorical variables, scaling the features, and preparing the data for training and testing. The model was compiled, trained, and evaluated using various optimization techniques.



**Results:**

- **Data Preprocessing:**

  - Target Variable: `IS_SUCCESSFUL`
  - Features: All columns except `IS_SUCCESSFUL`
  - Columns Removed: EIN, NAM. all other columns were either features or the target.

- **Compiling, Training, and Evaluating the Model:**

  - Neural Network Model: The model architecture consisted of a few hidden layers with varying neuron counts and activation functions. The output layer used a sigmoid activation function for binary classification.
  - Performance:
    - First Run (No Checkpoint at 50 Epochs): Loss: 0.6556, Accuracy: 0.7165
    - Second Run (Checkpoints at 50 Epochs): Loss: 0.7387, Accuracy: 0.7143
    - Third Run (Optimized, No Checkpoint, 30 Epochs): Loss: 0.6229, Accuracy: 0.7262
  - Achieving Target Performance: The target performance was not explicitly stated, but the model achieved accuracy in the range of approximately 0.714 to 0.726, which could be considered decent.
  - Steps to Improve Performance: Different optimization techniques were applied, including adjusting the number of neurons and layers, using different activation functions, and changing the number of epochs. While accuracy was improved in the third run compared to the baseline, further experimentation may be needed to achieve even better results.

  

**Summary:** 

The deep learning model was able to achieve reasonable accuracy in predicting the success of funding applications. The different optimization attempts demonstrated the impact of varying architectural and training parameters on model performance. For further improvement, feature engineering, additional data collection, or addressing class imbalances could help enhance model accuracy. 
