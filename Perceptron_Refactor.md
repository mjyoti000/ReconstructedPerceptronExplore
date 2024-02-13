# ReconstructedPerceptronRefactor 
1. Data Loading: Load the penguin dataset from a specified URL.

2. Data Preprocessing: Preprocess the dataset by dropping rows with missing values and selecting relevant columns (body mass, bill depth, and species).

3. Data Filtering: Filter out one species ('Adelie') to create a dataset with only two classes.

4. Data Transformation: Convert the features and labels into PyTorch tensors for further processing.

5. Data Splitting: Split the dataset into training and validation sets.

6. Normalization: Normalize the features in the training and validation sets using mean and standard deviation.

7. Model Initialization: Create an instance of the Perceptron model with specified parameters (input size, random seed, learning rate, verbosity).

8. Initial Evaluation: Compute the initial predictions on the training and validation data without training the model. Calculate and print the initial training and validation accuracies.

9. Decision Boundary Definition: Calculate the slope and intercept of the decision boundary based on the initialized weights of the Perceptron.

10 Decision Boundary Plotting: Plot the decision boundary along with the training data points, coloring them according to their labels ('Gentoo' or 'Chinstrap').

11. Model Training: Train the Perceptron model using the training data. Monitor the updates with a "u" and no updates with a "." per instance during training. Collect the sequence of training and validation accuracies for each epoch.
 
12.Final Evaluation: Calculate and print the final training and validation accuracies of the trained model.

13. Training Curves Visualization: Create a DataFrame to store the training and validation accuracies for each epoch during the training process. This can be used for further analysis and visualization.
