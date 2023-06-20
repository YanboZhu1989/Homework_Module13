# Venture Funding with Deep Learning

## Description
This project aims to create and optimize a binary classification model using neural networks. The dataset contains various features of Alphabet Soup–funded startups and the target is to predict whether these startups will be successful or not. The project is divided into three main sections: Data Preparation, Neural Network Model Creation & Evaluation, and Model Optimization.

## Prerequisites
You need to have installed:
- Python 3.7+
- Pandas
- Scikit-learn
- TensorFlow
- Keras

## Usage
 __Data Preparation:__ The 'applicants_data.csv' file is read into a Pandas DataFrame. Identify the categorical variables and the data is then split into features (X) and target (y) datasets, where "IS_SUCCESSFUL" defines the target dataset. The data is then split into training and testing datasets and scaled using StandardScaler.
 
__Neural Network Model:__ Creation & Evaluation: A binary classification deep neural network model is created using TensorFlow's Keras. The model is then compiled and fit using the binary_crossentropy loss function, the adam optimizer, and accuracy as the evaluation metric. The model is then evaluated to calculate its loss and accuracy. The model is saved and exported as an HDF5 file, 'AlphabetSoup.h5'.

__Model Optimization:__ 2 more attempts are made to optimize the model using various techniques such as reducing and adding more neurons to a hidden layer, adding more hidden layers and adjusting the number of epochs in the training regimen. The accuracy scores of each model are displayed and compared. Each model is saved as an HDF5 file.
