# DSC550-CNN-Model-Gender-Classification
An assignment for DSC550 (Neural Networks and Deep Learning) at GCU that focused on building a convolutional neural network (CNN) to analyze images of people's faces and classify them as either male or female.

Check out the full report [here.](https://github.com/jhould007/DSC550-CNN-Model/blob/master/CNN%20Model.ipynb)

<b>NOTE</b> The data I used to train the model is not available in this repository. If you would like to view it and potentially play around with it yourself, [here is the link to the dataset page on Kaggle.](https://www.kaggle.com/datasets/humairmunir/gender-recognizer)

# Assignment Instructions
The aim behind CNN is to classify images and text within large amounts of data in order to train a neural network to identify them with as close to 100% accuracy as possible. 

In this assignment, students will build and train a convolutional neural network (CNN) to recognize an image from a set. The general idea is that you will use a large set of images to train the neural network, then you will use it to identify an image presented to it.

# Assignment Instructions
Complete the following steps, then write a comprehensive technical report as a Python Jupyter notebook (to include all code, code comments, all outputs, plots, and analysis). Make sure the project documentation contains a) problem statement, b) algorithm of the solution, c) analysis of the findings, and d) references.

1. Browse the Kaggle "Datasets," located in the topic Resources.
2. Select one dataset for your project.
3. Write a short description of the dataset and what your CNN will recognize.
4. Import the appropriate libraries: tensorflow, keras, numpy, glob, matplotlib, MaxPooling2D, and any others that would fit your model.
5. Initialize the CNN.
6. Utilize the following arguments to add a convolutional layer: Filters, Kernel_size, Padding, Activation Function – Relu, and Input shape.
7. Downsample the images by applying a pooling operation.
8. Did you choose max pooling, average pooling, or global pooling? Explain which type of pooling you used and why. What are the advantages and disadvantages of your pooling choice?
9. Repeat steps 5–7 to add 3 more convolutional layers.
10. Convert the dataset into a 1-D array for input into the next layer (flattening the dataset), which is fully linked.
11. Use the dense class to create a fully connected layer (relu activation) and output one (softmax activation).
12. Train, then appraise the CNN you just created. Compile the CNN model using compile, with three parameters:
    - Loss Function: use categorical_crossentropy
    - Optimizer: your choice (Adam, Momentum, Nesterov Accelerated Gradient, or Min-Batch Gradient Descent).
    - Metrics Arguments: Accuracy to evaluate performance. Fit the model on the training set with at least 85 iterations (epochs). Evaluate the result. Compare the accuracy and loss function for both the training and test dataset. Plot the loss graph. Plot the accuracy graph.
13. Discuss how the CNN model is utilized in recognizing the images from the dataset and which optimizer provides for the performance model (highest accuracy and how many times to get to that level) the overall performance of your model. Justify your choice of optimizer by comparing it to two other optimizers.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.
This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.
You are not required to submit this assignment to LopesWrite.
