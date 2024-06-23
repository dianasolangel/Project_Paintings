# Best paintings of all time Classification Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Results](#results)

## Introduction
In this project as an art enthousiast I took interest in classifying the best paintings of all time to be able to get their artistic mouvement or genre, for that I used OpenCV and a convolutional neural network (CNN) implemented with TensorFlow. The goal was to accurately categorize paintings into various styles using image processing and machine learning.

## Features
- Image preprocessing with OpenCV
- CNN model built with TensorFlow
- Visualization of results`

## Dataset

## File explanation

```bash
┌── artist.csv
├── paintings_code.ipynb
└── model1.h5
```
- artist.csv: CSV file that contains information about the paintings and their corresponding artists (name, years, genre, nationality, paintings).
- paintings_code.ipynb: Jupyter Notebook that includes the code for data preprocessing, model training, and evaluation.
- model1.h5: The trained model saved in HDF5 format, which can be loaded for making predictions.

## Metrics on test data

- Test Loss: 0.12177721410989761
- Test Accuracy: 0.9671434760093689
- Test Precision: 0.653333306312561
- Test Recall: 0.056064072996377945

## Results

Example of some of the predictions obtained:

<img width="481" alt="Capture d’écran 2024-06-23 à 18 41 30" src="https://github.com/dianasolangel/Project_Paintings/assets/87640597/66471a0e-1094-4de1-970b-8468e7139b08">
<img width="536" alt="Capture d’écran 2024-06-23 à 18 41 12" src="https://github.com/dianasolangel/Project_Paintings/assets/87640597/127af7b2-93b5-4f8c-bdd6-55bb7f690c3c">
<img width="489" alt="Capture d’écran 2024-06-23 à 18 37 58" src="https://github.com/dianasolangel/Project_Paintings/assets/87640597/e41f3d3b-e687-4ef4-a3ae-8ebdeffde459">

