# Pytorch News Classifier

## A simple multilayered perceptron neural network built using PyTorch.
This network's job is to classify news based on it's headline and a small content sample.

News can be classified as one of the following labels/categories: 
- Sports
- Business
- Politics
- Health
- Tech
- Entertainment

## Data

A huggingface dataset was used, [here](https://huggingface.co/datasets/okite97/news-data/viewer/okite97--news-data/train) you can check it out.

> Stop-words and minimum token ocurrence were used to pre-process the data.

## Architecture

**Input vector** is a one-hot-encoding of the individual news vocabulary.

**1 Hidden Layer** of 6 neurons and a **Softmax** activation function

## Result

Acurracy was about **85%.**

Cleary there's a lot of room to improve, especially given the fact that the network is really simple!

> **Note**: This project was an assignment of my Natural Language Processing class.