## Deep Learning Nanodegree Foundation Project From Udacity

## Face Generation using Deep Convolutional Generative Adversarial Network

In this project, you can define and train a DCGAN on a dataset of faces. The main goal is to get a generator network to generate new images of faces that look as realistic as possible! The project is broken down into parts from loading in data to defining and training adversarial networks. 

## Libraries utilized

- **NumPy** - a fundamental package for scientific computing in python
- **Pandas** - an ease-to-use python library for manipulating data structures and performing data analysis
- **Jupyter Notebook** - tool that allows the creation of documents with live code
- **Matplotlib** - a plotting library for the Python programming language and its numerical mathematics extension NumPy.
- **PyTorch** - an open source machine learning library
- **Pickle** - the standard way of serializing objects in Python.

## Download Datasets
Download [CelebFaces Attributes Dataset (CelebA)](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip). Extract the file in the home directory of this notebook for further loading and processing. After extracting the data, you should be left with a directory of data *processed_celeba_small/*

## Instruction

1. Install [Anaconda](https://www.anaconda.com/distribution/).
2. Download the project
3. cd into the project folder
4. Run the code below to create and activate new environment

```
conda create --name face_gen_proj_env
```
 - Mac/Linux: 
```
source activate face_gen_proj_env 
```
 - Windows:
```
activate face_gen_proj_env
```
Install required libraries. For example, 
```
conda install numpy pandas matplotlib
```
```
jupyter notebook
```
