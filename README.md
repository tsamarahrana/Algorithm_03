# Convolutional Neural Network
This is the code provided for Assignment 5 as part of Algorithm course. A Convolutional Neural Networks (CNNs) is implemented on MNIST dataset which consists of images (28x28 size) and labels(classes).

# Requirements
The required libraries for the CNN impelementation are : 
- Tensorflow : used for deep learning or machine learning problems
- Numpy : used to perform a wide variety of mathematical operations
- Matplotlib.plot : used for visualizations

# Model 
Three different CNNs models used, with 1 convolution layers and 3 layers which are 3,5 and 7. 
![Screen Shot 2022-06-14 at 17 20 15](https://user-images.githubusercontent.com/55730503/173529551-12cbcbac-2104-4acb-aded-1945d212b119.png)

# Training and Training Loss
Choosen optimizer and loss function for training loss.
![Screen Shot 2022-06-14 at 17 22 21](https://user-images.githubusercontent.com/55730503/173530032-420375f4-153a-4309-8749-902e91af2629.png)
Train the model for 5 epochs. 
![Screen Shot 2022-06-14 at 17 21 38](https://user-images.githubusercontent.com/55730503/173530040-2acdb81f-bd1a-4534-af68-f326ec73d770.png)

# Test Accuracy 
Evaluate model by testing it for the test data set.
Test loss and accuracy for model with 3 layers
![Screen Shot 2022-06-14 at 17 27 06](https://user-images.githubusercontent.com/55730503/173531402-4d212ac9-b996-410c-96b6-d94cc034193b.png)
Test loss and accuracy for model with 5 layers
![Screen Shot 2022-06-14 at 17 38 55](https://user-images.githubusercontent.com/55730503/173533518-3250408f-25bd-45df-8456-885b6d300bff.png)
Test loss and accuracy for model with 7 layers


# Image and corresponding probability that are predicted right 
![Screen Shot 2022-06-14 at 17 27 45](https://user-images.githubusercontent.com/55730503/173531396-ae6ab668-9dc4-4ef6-84a2-470aee910cd3.png)


# Image and coressponding probability that are predicted wrong
