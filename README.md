# Deep Learning Challenge - Alphabet Soup Funding Predictor

## Background
The nonprofit foundation Alphabet Soup aims to enhance its funding selection process by leveraging machine learning and neural networks. Your task is to develop a binary classifier using a provided dataset containing information on over 34,000 organizations that have received funding from Alphabet Soup. The goal is to predict the success of ventures based on various features. The project involves preprocessing the data, building and training a neural network, optimizing the model, and finally, writing a comprehensive report on the analysis.

## Before You Begin
Follow the instructions to set up your project repository named "deep-learning-challenge" and download the necessary files from the provided links. Ensure that you use Google Colab for this assignment.

## Files
Download the Module 21 Challenge files to get started.

## Step 1: Preprocess the Data
1. Upload the starter file to Google Colab and follow the provided instructions to preprocess the dataset.
2. Identify target and feature variables.
3. Drop unnecessary columns (EIN and NAME).
4. Determine unique values for each column.
5. For columns with more than 10 unique values, analyze data points for each value.
6. Bin "rare" categorical variables together in a new value, "Other," and verify the success of binning.
7. Use pd.get_dummies() to encode categorical variables.
8. Split data into features array (X) and target array (y).
9. Split preprocessed data into training and testing datasets.
10. Scale the training and testing features datasets using StandardScaler.

## Step 2: Compile, Train, and Evaluate the Model
1. Continue using the Colab file from Step 1.
2. Design a neural network model using TensorFlow and Keras.
3. Create hidden layers with appropriate activation functions.
4. Compile and train the model.
5. Implement a callback to save the model's weights every five epochs.
6. Evaluate the model using test data to determine loss and accuracy.
7. Save and export results to an HDF5 file named "AlphabetSoupCharity.h5."

## Step 3: Optimize the Model
1. Create a new Colab file named "AlphabetSoupCharity_Optimization.ipynb."
2. Import dependencies and preprocess the dataset as in Step 1, adjusting for any modifications made during optimization.
3. Design a neural network model, incorporating at least three model optimization methods.
4. Save and export results to an HDF5 file named "AlphabetSoupCharity_Optimization.h5."

## Step 4: Write a Report on the Neural Network Model
### Overview of the Analysis
Explain the purpose of the analysis.

### Results
#### Data Preprocessing
- Target variable(s)
- Feature variable(s)
- Variables to be removed

#### Compiling, Training, and Evaluating the Model
- Number of neurons, layers, and activation functions
- Achievement of target model performance
- Steps taken to increase model performance

### Summary
Summarize the overall results, provide a recommendation for a different model, and explain the rationale behind the recommendation.

## Step 5: Copy Files Into Your Repository
1. Download Colab notebooks to your computer.
2. Move them into the "Deep Learning Challenge" directory in your local repository.
3. Push the added files to GitHub.

## Requirements
Ensure compliance with the specified requirements for each step, and aim to achieve the allocated points for each task. Optimize the model to achieve a target predictive accuracy higher than 75%, using various methods outlined in the instructions. The final submission should include the necessary files in your GitHub repository.
