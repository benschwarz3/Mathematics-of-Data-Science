# AlexNet Data Classification

# Overview/Purpose
Animal data set

Using AlexNet to help identify the distinguishing characteristics in animals to determine whether they are classified as “land” (terrestrial) or “sea” (aquatic) creatures.

This project helps to encapsulate just how effective AI and AlexNet can be with small, intricate tasks. If AlexNet is able to perform well with this task, it could pave the way for the future integration of AlexNet and other AI recognition systems into more and more everyday tasks. 

<img width="366" alt="Picture1" src="https://user-images.githubusercontent.com/123206563/235856430-225bfd44-17dc-4f29-afab-b189d77f8c6b.png">

# Animals
<img width="226" alt="Picture2" src="https://user-images.githubusercontent.com/123206563/235855001-3c7e7655-fe82-42ab-86b1-6ed903206ca3.png">

<img width="207" alt="Picture3" src="https://user-images.githubusercontent.com/123206563/235855023-73c04151-dba7-4473-a726-8faf19bfdb0d.png">

<img width="194" alt="Picture4" src="https://user-images.githubusercontent.com/123206563/235855042-6222523f-006f-4868-b0ce-14dd2b950e92.png">

<img width="207" alt="Picture5" src="https://user-images.githubusercontent.com/123206563/235855054-d8b6a4bd-2a8c-4f3d-8941-08eb5eac2ce3.png">

<img width="263" alt="Picture6" src="https://user-images.githubusercontent.com/123206563/235855073-c3a5a9d9-c64c-44f4-a4c8-9bcc474d358f.png">

# Real World Application
AI use with classification/feature analysis is already seen all over 
  Facial recognition, traffic cameras, weather detection, criminology field, etc.

If AlexNet is successful, this could help pave the way for further use, integration, and development of AlexNet and AI in detection/feature analysis
  Continuous improvement/development as well as new advancements with military technology, criminology field, medical field, agriculture, etc. 

Applied AI View - produce commercially viable smart systems

<img width="268" alt="Picture7" src="https://user-images.githubusercontent.com/123206563/235855344-8e7ed64c-c595-4732-a258-d5e08739df2f.png">

# What is AlexNet?

AlexNet is a deep convolutional neural network that was designed for image classification tasks. Specifically, AlexNet processes an input image through a series of convolutional layers, activation functions, pooling operations, and fully connected layers to predict the probability of the image belonging to a set of predefined classes.

Developed in 2012, AlexNet is composed of 8 layers, 5 convolutional layers and 3 fully connected layers, with a total of 60 million parameters. It uses ReLU activation functions instead of traditional activation functions, allowing faster training and improved accuracy.

<img width="412" alt="Picture8" src="https://user-images.githubusercontent.com/123206563/235855461-11884d23-7c6a-4f18-8bec-09572d57fc1c.png">

# Image Convolution

AlexNet uses convolutional layers for image feature extraction. A convolutional layer applies a set of filters to an input image and produces a set of output feature maps

Each filter is applied to each region of the input image, and the output feature map is generated by computing the dot product between the filter and the input patch of the image at each spatial location 

<img width="295" alt="Picture9" src="https://user-images.githubusercontent.com/123206563/235855548-c489c6f3-3715-44e0-99d0-01ce78764ff3.png">

# Feature Extraction

AlexNet uses a set of convolutional layers for feature extraction from the input image. The filters in these layers are designed to learn local patterns and features from the image, including edges, textures, and shapes

These features are gradually learned and then combined across the layers to form higher-level and more abstract representations of the image

<img width="356" alt="Picture10" src="https://user-images.githubusercontent.com/123206563/235855658-5172c2c2-4c23-4c24-bbec-7efb8025b93b.png">

# Max Pooling

AlexNet uses max pooling layers for reducing the spatial dimensions of the features maps produced by the convolutional layers. Max pooling partitions each feature map into non-overlapping rectangular regions and outputs the maximum value within each region

<img width="456" alt="Picture11" src="https://user-images.githubusercontent.com/123206563/235855795-14ef11ac-0a05-42ef-9c6e-58fd04265e21.png">

# Average Pooling

Average pooling is used in AlexNet’s last fully connected layer to reduce the number of parameters in the network and prevent overfitting, while preserving some spatial information that may be useful for classification. By taking the average of the feature maps, the network is able to obtain a single feature vector that summarizes the most important information from each feature map

The output of the average pooling layer is passed through a softmax activation function to compute the class probabilities for the input image. The softmax function normalizes the output of the average pooling layer into a probability distribution over different classes in the dataset, allowing the network to make a prediction about the most likely class label for the input image

<img width="190" alt="Picture12" src="https://user-images.githubusercontent.com/123206563/235855847-adcbc824-6efe-4fad-8497-8ae931216597.png">

# ReLU

AlexNet uses the ReLU (Rectified Linear Unit) activation function in the convolutional and fully connected layers. This introduces non-linearity to the network, which allows it to learn more complex and non-linear functions of the input data. ReLU function is defined as f(x) = max(0,x) where x is the input to the function. ReLU simply returns the input if it is positive and returns 0 if the input is negative

![Picture13](https://user-images.githubusercontent.com/123206563/235855954-1580792e-7ab8-450a-be52-d89335550edc.jpg)

# Dropout

Dropout regularization is used in the fully connected layers to prevent overfitting. Dropout randomly drops out a fraction of the units in a layer during training, forcing the remaining units to learn more robust and diverse features. Specifically, Dropout sets the output of each unit to 0 with a certain probability, independent of other units

<img width="366" alt="Picture14" src="https://user-images.githubusercontent.com/123206563/235856012-6ba37ff0-6034-4c72-8508-77a94e0b0881.png">

# Results

<img width="134" alt="Picture15" src="https://user-images.githubusercontent.com/123206563/235856104-b4a216ae-9604-4dd4-9950-a82170dee09a.png">

While there is room for improvement given the resulting data accuracy differences, this project clearly shows that AlexNet is ready to contribute to the real-world in numerous different ways. 

https://youtu.be/Ue3yt39xKHE 
