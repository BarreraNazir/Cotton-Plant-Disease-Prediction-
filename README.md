 # Cotton-Plant-Disease-Prediction-Using-Deep-Learning

**Problem Identification** 

The production of cotton reducing gradually over the year because of major cotton diseases which impact their production very much on some common diseases like insect attacks, charcoal rot, and many more. The problem will be solved if the farmer gets to know about the plants which are infected and diseased in the early stages of their growth so that farmers can use pesticides and different medicinal pieces of equipment to sprinkles medicines over plants and save their crops from diseases in early stages of production.

**Goal**  

Automatic system designed to detect the disease from cotton plant leaves using convolutional neural network.

**Getting Started**

The project is broken down into the following steps:

* Importing Libraries and Data

* Model Building and Testing

**Importing Libraries and Data**

 * Importing Libraries:
    
      Keras, NumPy, and Matplotlib Libraries are used in Jupyter NoteBook (Google Colab) for building model.

 * Dataset:

      The Cotton Plant datasets is available machine learning repository maintained by the University of California, Irvine. The dataset contains 2,310 samples of diseased cotton leaf, diseased cotton plant, fresh cotton leaf, and fresh cotton plant. It contains train, validation, and test images which is used to build a model to predict whether a cotton plant is fresh or infected by some disease.
      
**Model Building and Testing**:
    
   “Convolution Neural Network” (CNN) is selected to build the model. I created my own CNN architecture and it works well on the training and as well as testing dataset. It gives me more than 98% accuracy on training and validation data set in just 500 epochs. I am trying to increase accuracy with more data and epochs.
