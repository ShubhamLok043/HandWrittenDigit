# HandWrittenDigit
Research in the handwriting recognition subject is centered on deep learning strategies and has accomplished breakthrough overall performance in the previous couple of years. Convolutional neural networks (CNNs) are very powerful in perceiving the structure of handwritten digits in ways that assist in automated extraction of features and make CNN the most appropriate technique for solving handwriting recognition problems. Here, our goal is to attain similar accuracy through the use of a pure CNN structure.

![image](https://user-images.githubusercontent.com/114350965/192151884-68b64e51-cf98-4bd0-b531-69923e29253d.png)

At first, we have imported all the required libraries:

 

Keras : - Keras is an open-source high-level Neural Network library, It not only supports Convolutional Networks and Recurrent Networks individually but also their combination.
Tensorflow :- Tensorflow is a library that is used in machine learning and it is an open-source library for numerical computation

•	Importing mnist Dataset and splitting it into train and test (6:1)
 

The MNIST database (Modified National Institute of Standards and Technology database) is a large collection of handwritten digits. It has a training set of 60,000 examples, and a test set of 10,000 examples.
 


•	Re-shaping the data and converting it into matrix:

 

•	Creating a CNN Model:

  


•	Model Evaluation & Saving it as mnist_modeldigit.h5:

 

