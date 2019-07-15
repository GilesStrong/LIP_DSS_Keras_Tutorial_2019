[![DOI](https://zenodo.org/badge/174577255.svg)](https://zenodo.org/badge/latestdoi/174577255)

# Keras Tutorial - Originally presented at LIP Data Science School in (astro)particle physics and cosmology, Braga 2019: 
## Overview
This tutorial is designed to present neural networks from a practical, coding perspective and focus on their implementation via [Keras](https://keras.io/).
Four notebooks are found in the `notebooks` folder:
1. SGD_from_scratch uses a single neuron for trivial classification and regression tasks on pseudodata, implementing backpropagation and weight updates manually in Numpy. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/0_SGD_from_scratch.ipynb)
1. Basic_Keras_Classification introduces Keras, using a non-trvial, but basic classification problem. Additionally it teaches the class-based approach for model building in Keras. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/1_Basic_Keras_Classification.ipynb)
1. Basic_Keras_Regression uses the functional approach for model building in Keras to regress to a non-linear function. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/2_Basic_Keras_Regression.ipynb)
1. Basic_Application_Exercise is an exercise introducing working with an example of tabular data and training a simple classifier. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/3_Basic_Application_Exercise.ipynb)
1. Basic_Application_Exercise-Extended continues on from the previous exercise by looking at a more efficient treatment of categorical features, and how Keras Callbacks can be used to imporve training. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/4_Basic_Application_Exercise-Extended.ipynb)
1. Advanced_Application_Example draws on both functional and class-based model building approaches to build a classifier for a real-world example problem; event classifcation at the Large Hadron Collider. Additionally this notebook touches on some fundamental aspects of data science, including validation/test sets, data pre-processing, and model interpretation. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GilesStrong/LIP_DSS_Keras_Tutorial_2019/blob/master/notebooks/5_Advanced_Application_Example.ipynb)

## Running
The tutorial may either be run directly by installing the appropriate Python modules yourself, via Google Coolab using the badges, or via the Docker image via:
- `docker pull lipcomputing/data_science_school_2019:cpu-py36-keras_tutorial`
- `docker run -it -p 8888:8888 lipcomputing/data_science_school_2019:cpu-py36-keras_tutorial`
