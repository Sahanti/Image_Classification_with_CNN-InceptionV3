**Image Classification using CNN and InceptionV3**

This project demonstrates image classification using Convolutional Neural Networks (CNN) and the InceptionV3 model. The dataset used contains three categories: Cars, Dogs, and Tables, with over 100 images in each category.

**Setup**

To run this project, ensure you have the following libraries installed:

numpy
PIL
tensorflow
matplotlib
google.colab

**Instructions**

Import the required libraries.
Create your dataset featuring three custom categories of at least 100 images each.
Split the data between 80% training and 20% test sets.
Preprocess the data as needed.
Create a CNN-based model to learn from the training set.
Train the model and visualize the training data and model.
Make predictions on the test data and compare them to the expected categories.
Use the InceptionV3 model and add a LinearLayer on top of it.
Train the InceptionV3-based model and compare the accuracy with the CNN model.

**Results**
The CNN model achieved a training accuracy of 0.94 and a validation accuracy of 0.83. The InceptionV3 model achieved a similar accuracy of 0.83, indicating that the CNN model performed better for this dataset.

