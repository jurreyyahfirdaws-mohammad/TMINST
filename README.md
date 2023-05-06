## TMINST
# Abstract:
This project involved implementing a Convolutional Neural Network (CNN) using PyTorch, a popular deep learning framework, to accurately classify images of digits from 0 to 9. The dataset used was the MNIST dataset, which contained 60,000 training images and 10,000 test images. The goal was to achieve a high level of accuracy in correctly identifying the digits.

# Methodology:
The methodology used in this project involved implementing a Convolutional Neural Network (CNN) using PyTorch to classify images of digits from 0 to 9.

Firstly, I constructed the CNN architecture, which consisted of two convolutional layers that extracted features from the images, followed by two fully connected layers that produced the final classification output.

Next, I used the MNIST dataset, which contained 60,000 training images and 10,000 test images of digits ranging from 0 to 9. The images were normalized and reshaped into a 4-dimensional array to be fed into the CNN. The labels were also reshaped into a 1-dimensional array for classification.

I then trained the CNN using the Cross Entropy Loss function, which is commonly used for multi-class classification tasks, and the Adam optimizer, which is a popular gradient descent optimization algorithm. The model was trained for 10 epochs using a GPU.

Finally, I evaluated the performance of the CNN on the test dataset by calculating the accuracy of the model in classifying the digits. The accuracy was determined by comparing the predicted labels of the CNN with the true labels of the test dataset.

#Dataset:
The MNIST dataset is comprised of balanced images of digits from 0 to 9, with 2990 examples of each class. The images are pre-processed by normalizing and reshaping them into a 4-dimensional array, representing stacked images, while the labels are reshaped into a 1-dimensional array. Overall, this project aimed to effectively leverage deep learning techniques to accurately classify digits in images, with a focus on using the PyTorch framework and CNN architecture to achieve optimal results. https://www.kaggle.com/datasets/nimishmagre/tmnist-typeface-mnist
