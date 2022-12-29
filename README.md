# ROBT 414
# Title: Emotion Detection from text using PyTorch and facial expression generation in Blender using OpenPose
# Authors: Dana Aubakirova, Zhamilya Saparova, Nurdaulet Zhuzbay

## Contents
1. [General-info](#general-info)
2. [emotion-detection](#emotion-detection)
3. [openpose-to-blender](#openpose-to-blender)
4. [Libraries](#libraries)

## General-info
This project  aims to develop a deep-learning based model that allows for the accurate semantic analysis of the text, that in combination with advanced 3D animation softwares could produce human-like facial expressions. 

## emotion-detection

### The Project Notebook

#### This is the the emotion_detection.ipynb file containing the detailed implementation of the LSTM model for emotion detection from text. It includes the dataset explanation, the pipeline of the model, training output, detailed comments as well as results.

### Dataset

####The datasets folder contains the train.csv (132 instances and labels), and test.csv (56 instances and labels) used for training and testing the model.

#### glove.6B.50d.txt is file containing pre-trained GloVe embeddings used for word-vector representations. The embedding can be downloaded from [here](https://worksheets.codalab.org/rest/bundles/0x97c870dd60eb4f0fa53f257978851c60/contents/blob/glove.6B.50d.txt).

## openpose-to-blender

### in this folder you will find the .blend, .json files for facial key points and facial_transfer_blender.py. Please, visit, separate README file in this folder to see how to call the script.  

## Libraries
***
A list of main libraries and tools used within the project:
* [PyTorch](https://pytorch.org)
* [GloVe](https://nlp.stanford.edu/projects/glove/)
* [Pandas](https://pandas.pydata.org)
* [Matplotlib](https://matplotlib.org/)
* [Openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)

