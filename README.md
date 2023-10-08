# dog_classification_kaggle_competition

End-to-end Multi-class Dog Breed Classification
This notebook builds an end-to-end multi-class image classifier using Rensorflow 2.0 and tensorFlow Hub.

1. Problem
Identifying the breed if the dog given an image of a dog

When i'm sitting a the cafe and I take a photo of dog, I want to know what breed of dog it is

2. Data
The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/competitions/dog-breed-identification/data

3. Evaluation
The evaluation is a file with prediction probability for each dog breed of each image.

https://www.kaggle.com/competitions/dog-breed-identification/overview

4. Features
Some information about the data:

We are dealing with images (unstructured data) so it's probably best we use deep learning/transfer learing.
There are 120 breeds (this means there are 120 different classes).
There are around 10,000+ images in the training set
There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them)
