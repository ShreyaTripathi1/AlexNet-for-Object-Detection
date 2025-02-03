# Implementing AlexNet architecture for Object Detection

This project trains a neural network (AlexNet) to classify images from two datasets: SVHN (Street View House Numbers) and Fashion-MNIST.
- ```SVHN Dataset```: Contains images of street numbers (0-9). The goal is for the model to recognize these digits from the images.
-	```Fashion-MNIST Dataset```: Contains grayscale images of clothing items (like T-shirts, shoes, and dresses). The model learns to classify these clothing categories. 


## About AlexNet
AlexNet is a deep convolutional neural network designed for image classification tasks. This was the first architecture that used GPU to boost the training performance. It captures complex patterns in images through multiple convolutional layers, followed by **ReLU activations**, **max-pooling layers**, and fully connected layers. These components allow the model to **learn hierarchical features** from the input data, making it effective for a wide range of visual recognition tasks. In this project, AlexNet was applied to two distinct datasets: SVHN (Street View House Numbers) and Fashion-MNIST.

In 2012, AlexNet produced ground-breaking results in the ImageNet Large Scale Visual Recognition Challenge (ILSVRC). It outperformed prior CNN architectures greatly and set the path for the rebirth of deep learning in computer vision.
Several architectural improvements were introduced by AlexNet, including the use of rectified linear units (ReLU) as activation functions, overlapping pooling, and dropout regularisation. These strategies aided in the improvement of performance and generalisation



## Architechture
AlexNet consists of **8 layers**, including 5 convolutional layers and 3 fully connected layers, which makes it simpler to train and less prone to overfitting on smaller datasets. It uses traditional stacked convolutional layers with max-pooling in between. Its deep network structure allows for the extraction of complex features from images.

- The architecture employs overlapping pooling layers to reduce spatial dimensions while retaining the spatial relationships among neighbouring features.
- Activation function: AlexNet uses the ReLU activation function and dropout regularization, which enhance the model’s ability to capture non-linear relationships within the data.


| Features      | AlexNet       |
| ------------- | ------------- |
| Architecture  |Deep (8 layers)|
|Activation Function| ReLU  |
| Pooling  | Overlapping  |
| Convolution  | Consecutive  |
| Dimensionality  | No reduction |
| Regularization  | Dropout  |
 

## Conclusion
  - On the SVHN dataset, which consists of images of street numbers (0-9), AlexNet achieved an impressive accuracy of **91.71%**, demonstrating its ability to effectively recognize digits.
  - For the Fashion-MNIST dataset, which contains grayscale images of various clothing items, the model achieved an accuracy of **90.08%**. These results show that AlexNet is capable of performing well on both digit and clothing classification tasks, showcasing its versatility and effectiveness in handling different types of visual data.
