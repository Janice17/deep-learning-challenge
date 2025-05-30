# deep-learning-challenge
# Code Source:
Jupyter Notebook code (Starter_Code.ipynb and AlphabetSoupCharity_Optimization.ipynb)
# Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
## Step 1: Preprocess the Data
Using your knowledge of Pandas and scikit-learn’s StandardScaler(), you’ll need to preprocess the dataset. This step prepares you for Step 2, where you'll compile, train, and evaluate the neural network model. Used Google Colab to.  
1. Read in the data into Pandas DataFrame.  
2. Dropped the EIN and NAME columns.  
3. Determined the number of unique values for each column.  
4. For those columns that have more than 10 unique values, determine the number of data points for each unique value.  
5. Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.  
6. Use pd.get_dummies() to encode categorical variables.  
7. Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.  
8. Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.
## Step 2: Compile, Train, and Evaluate the Model
Using TensorFlow, I designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. I compiled, trained, and evaluated my binary classification model to calculate the model’s loss and accuracy.  
1. Continue using the file in Google Colab in which you performed the preprocessing steps from Step 1.  
2. Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.  
3. Create the first hidden layer and choose an appropriate activation function.  
4. If necessary, add a second hidden layer with an appropriate activation function.  
5. Create an output layer with an appropriate activation function.  
6. Check the structure of the model.  
7. Compile and train the model.  
8. Create a callback that saves the model's weights every five epochs.  
9. Evaluate the model using the test data to determine the loss and accuracy.  
10. Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.
## Step 3: Optimize the Model
Using your knowledge of TensorFlow, optimize your model to achieve a target predictive accuracy higher than 75%.  
- Adjust the input data to ensure that no variables or outliers are causing confusion in the model.  
1. Create a new Google Colab file and name it AlphabetSoupCharity_Optimization.ipynb.  
2. Import your dependencies and read in the charity_data.csv to a Pandas DataFrame from the provided cloud URL.  
3. Preprocess the dataset as you did in Step 1. Be sure to adjust for any modifications that came out of optimizing the model.  
4. Design a neural network model, and be sure to adjust for modifications that will optimize the model to achieve higher than 75% accuracy.  
5. Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity_Optimization.h5.
## Write a Report on the Neural Network Model
Report is saved as Analysis.pdf
# References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.
