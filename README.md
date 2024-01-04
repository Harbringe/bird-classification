# bird-classification

This Python machine learning model notebook focuses on the task of image classification for 525 different bird species. The goal is to leverage advanced algorithms to accurately categorize and identify birds based on images.

## About the dataset:

This dataset comprises 525 bird species with a total of 84,635 training images, 2,625 test images (5 images per species), and 2,625 validation images (5 images per species). The dataset has undergone rigorous cleaning, eliminating duplicate and near-duplicate images, ensuring dataset integrity and preventing leakage between train, test, and validation sets. All images are in JPG format, sized 224 x 224 x 3 pixels, with each image featuring a single bird that occupies at least 50% of the pixels. The "birds.csv" file provides metadata such as file paths, labels, scientific names, and dataset designations. Notably, the dataset is unbalanced in terms of training set species distribution, with a minimum of 130 training images per species. It is important to acknowledge a gender bias, as approximately 80% of the images depict males and 20% depict females. The dataset's large size recommends using an image size of 150 x 150 x 3 for faster model training. It is advised to note that the classifier's performance may vary between male and female species images due to the gender distribution in the dataset.

The dataset is not included in this repository, follow the link to download the dataset: [BIRDS 525 SPECIES- IMAGE CLASSIFICATION](https://www.kaggle.com/datasets/gpiosenka/100-bird-species)

Refer to notebook file for further reference.
