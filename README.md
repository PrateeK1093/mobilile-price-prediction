# Problem Statement 
This is our Project titled "Mobile Price & Battery Life Prediction" in which we will be able to predict the Price of any Mobile phone and life of its battery from different parameters like Battery Power, Number of Sim slots, RAM, etc. We will use different Regression models to accomplish our task.
## Dataset

The dataset which we have used is "Mobile Price Classification" from Kaggle. Link-> https://www.kaggle.com/iabhishekofficial/mobile-price-classification . This is a Regression task in which our target variables will be: - 

a). Battery Life

b). Mobile Price 

## Model(s) Used

This needs to be a description of the model used and a brief overview of how it works in theory (e.g taken of a CNN Model): 

The network architecture used was a basic CNN model, with Max Pooling and ReLU Activation functions. Input images are resized to an optimal size and then fed into the **Convolutional layer**. These images are converted to their pixel values, which can be imagined as a three-dimensional matrix for the purpose of visualization. The **Convolutional layer** has a kernel. This kernel is generally a small matrix of specified kernel size mxnx3 (3 for RGB images). 
<br>

**Rectified Linear Unit (ReLU)** is the activation layer used in CNNs.The activation function is applied to increase non-linearity in the CNN. Images are made of different objects that are not linear to each other.


**Max Pooling:** A limitation of the feature map output of Convolutional Layers is that they record the precise position of features in the input. This means that small movements in the position of the feature in the input image will result in a different feature map. This can happen with re-cropping, rotation, shifting, and other minor changes to the input image. A common approach to addressing this problem from signal processing is called down sampling. This is where a lower resolution version of an input signal is created that still contains the large or important structural elements, without the fine detail that may not be as useful to the task.

## Future Work
Good ideas or strategies that you were not able to implement which you think can help  improve performance.
