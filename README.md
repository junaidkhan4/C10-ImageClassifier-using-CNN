# C10-ImageClassifier-using-CNN

**Dataset**
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images. The classes include:

Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck

**Requirements**
TensorFlow
NumPy
Matplotlib
scikit-learn

**Model Architecture**
The model is a basic CNN with the following architecture:

Convolutional layer with 32 filters and (3, 3) kernel size
Max pooling layer
Convolutional layer with 64 filters and (3, 3) kernel size
Max pooling layer
Convolutional layer with 64 filters and (3, 3) kernel size
Fully connected layer with 64 neurons
Output layer with 10 neurons


