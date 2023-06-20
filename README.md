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
 __Data Preparation:__ The 'applicants_data.csv' file is read into a Pandas DataFrame. Categorical variables are identified for encoding and potential features and target variables are identified. Irrelevant columns such as "EIN" and "NAME" are dropped. The categorical variables are then OneHotEncoded and
