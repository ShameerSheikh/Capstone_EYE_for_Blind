# Capstone_EYE_for_Blind
Analyzing the images to generate captions in text format and reading out the text in an audio format to help the Blind.

## Problem statement:

In this capstone project, we have to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset.
https://www.kaggle.com/datasets/adityajn105/flickr8k


## Objective:

1. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library.

2. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

## Sequence of Steps:

The major steps we performed are briefly summarised in the following four steps:

1. Data Understanding: Here, we load the data and understand the representation.
2. Data Preprocessing: In this step, we processed both images and captions to the desired format.
3. Train-Test Split: Combined both images and captions to create the train and test dataset.
4. Model Building: This is the stage where we created the image captioning model by building Encoder, Attention and Decoder model.
5. Model Evaluation: Evaluated the models using greedy search and BLEU score.


### Author: Shameer Sheik, UpGrad ML C56
