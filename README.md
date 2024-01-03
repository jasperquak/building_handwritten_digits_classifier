# Building a handwritten digits classifier

Aim of this project is to classify handwritten digits (0-9) with a predictive model. Different models are used: KNN (k nearest neighbors) and MLP (multilayer perceptron neural network), and compared in terms of accuracy: the percentage of correct predictions on 'unseen' data.

This project was a 'guided project' as part of learning data science with [Dataquest](https://www.dataquest.io).

## Results

To display the result, simply [click the .ipynb file](https://github.com/jasperquak/predicting_bike_rentals/blob/main/PredictingBikeRentals.ipynb) in this repository. It will open in a Notebook viewer.

## Reproduction

In case you want to reproduce the project in a Jupyter Notebook in your own environment.

Download both the .ipynb file. (There are no data files to download, as the data is imported with an in-built function of scikit-learn.)

Before starting Jupyter Notebook, ensure that you have the following packages installed:
* numpy
* matplotlib.pyplot
* sklearn.datasets
* sklearn.neighbors
* sklearn.metrics
* sklearn.model_selection
* sklearn.neural_network

## About the data source

The data that is used is a [hand-written digits dataset from UCI](https://archive.ics.uci.edu/dataset/80/optical+recognition+of+handwritten+digits). (A copy of this dataset is readily available from the scikit-learn packages though.)
