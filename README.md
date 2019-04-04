# mnist digit recognizer using cnn

Here keras is used using tensorflow backend

## Dataset
This dataset is downloaded from kaggle competition for mnist dataset

## Process
* First the dataset is loaded into `pandas.dataframe` and data is reshaped to get the spatial image
* Then the image display is done using `matplotlib.imgshow` and added lable to visualize the dataset
* Then the cnn architecture is  described and compiled
* Here a validation set is created to check validation and load weights from the best model
* The final model gave a acc of 99.079% of the test data set
* Finally model is used to predict the data for test.csv file

## Installation
* To run the notebook the following libraries need to be installed `numpy`, `pandas`, `keras`, `sklearn`.
* Then run the jupyter notebook. (It's better to use gpu enabled workspace for faster execution) 
