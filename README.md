# Land Cover Classification on DeepSat

This was was a practice project for me related to one of my internships. I wanted to get an idea of land cover classification before writing a custom code. 

## Dataset

The dataset I used was a subset of the National Agriculture Imagery Program (NAIP) dataset. Here the files were originally MAT files. But I obtained a subset of this dataset, with the MAT files converted to csv format from Kaggle.

Each image in the training and testing data is 28x28 pixels and consists of 4 bands - red, green, blue and near-infrared.

The training and test labels are one-hot encoded 1x6 vectors

The six land cover classes for classifcation are:  barren land, trees, grassland, roads, buildings and water bodies.

You can download the dataset by clicking this [link](https://www.kaggle.com/crawford/deepsat-sat6/download)

# Data info

- Xtrainsat6.csv: 324,000 training images, 28x28 images each with 4 channels

- ytrainsat6.csv: 324,000 training labels, 1x6 one-hot encoded vectors

- Xtestsat6.csv: 81,000 training images, 28x28 images each with 4 channels

- ytestsat6.csv: 81,000 training labels, 1x6 one-hot encoded vectors


# Notebook info

You can either run the Jupyter notebook locally or access the [Colab Notebook](https://colab.research.google.com/drive/1eGd28VqK8yOwkPwT8oJ2EjR5NFGENG97?usp=sharing)