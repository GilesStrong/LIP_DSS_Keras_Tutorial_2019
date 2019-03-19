# LIP Data Science School in (astro)particle physics and cosmology, Braga 2019: Keras Tutorial
## Overview
This tutorial is designed to present neural networks from a practical, coding perspective and focus on their implementation via [Keras](https://keras.io/).
Four notebooks are found in the `notebooks` folder:
1. SGD_from_scratch uses a single neuron for trivial classification and regression tasks on pseudodata, implementing backpropagation and weight updates manually in Numpy.
1. Basic_Keras_Classification introduces Keras, using a non-trvial, but basic classification problem. Additionally it teaches the class-based approach for model building in Keras.
1. Basic_Keras_Regression uses the functional approach for model building in Keras to regress to a non-linear function.
1. Application_Example draws on both functional and class-based model building approaches to build a classifier for a real-world example problem; event classifcation at the Large Hadron Collider. Additionally this notebook touches on some fundamental aspects of data science, including validation/test sets and data pre-processing.

## Running
The tutorial may either be run directly by installing the appropriate Python modules yourself, or via the Docker image via:
- `docker pull lipcomputing/data_science_school_2019:keras_tutorial`
- `docker run -it -p 8888:8888 -v [path/to/notebooks]:/notebooks lipcomputing/data_science_school_2019:keras_tutorial`