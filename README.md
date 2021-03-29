# Fashion Class Classification
This repo consists of the Fashion Class Classification Case Study from Super Data Science's course, Machine Learning Practical: 6 Real-World Applications.

# Problem Statement
Need to classify a dataset of 10,000 images, each of which is a 28x28 Grayscale Image, into one of the associated 10 Classes. For training of the model, a dataset of 60,000 images is also provided.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.

# Model Used
The case study utilises a Convolutional Neural Network (CNN) Model, with a total of 32 Filters / Feature Selectors, each having a size of 3x3, then a Max Pooling Layer of size 2x2, then the Flatten Layer, and then a Dense Layer with 64 Neurons, and the final Dense (Output) Layer, classifying the Input into 1 of the 10 Associated Classes.

# Libraries Used
Pandas
Numpy
Matplotlib
Seaborn
Scikit Learn
Keras
