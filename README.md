[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guiwitz/MLCV/blob/main/)

# Machine Learning for Computer Vision

This repository contains material for the Machine Learning for Computer Vision course of the Data Science Lab of the University of Bern. With this course you can learn how to create, train and use Neural Networks for Computer Vision. The course is at the same time an introduction to PyTorch and shows how to handle datasets, and use higher level training packages like PyTorch-Lightning. Most of the examples use small or synthetic datasets, making it possible to run most of the material on laptop CPU. However, the course can also be run on Google Colab where GPU can be used for free.

## Installation

The necessary packages can easily be installed locally using conda with the [environment.yml](environment.yml) file to create an environment:

```
conda env create -f environment.yml
```

This environment can then be activated and Jupyter started with:

```
conda activate CASMLCV
jupyter lab
```

## Datasets

You can find the simple demo datasets on [Zenodo](https://zenodo.org/record/4465181). The data are stored in a zip file that you can directly download with [this link](https://zenodo.org/record/4465181/files/data.zip?download=1). This zip file should be unzipped and put at the same level as the ```notebooks``` folder of this repository for paths to work properly.