
# Poacher Detection with Convolutional Neural Network

It should work in any compatable python version.

You could run TensorFlow for CPU Only ( or/and GPU).

kaggle repository (+augmented) image dataset and .npy  files https://www.kaggle.com/georgiosgiouvanis/poacher-detection-3classes

Version Used

python : 3.8.5

numpy : 1.18.5

Keras : 2.4.0

tensorflow : 2.3.0

Use your own images: You will find code to resize images to prefered dimentions, also code to augment your data.

step 1: Create virstual inviroment virtual environment. Install miniconda+keras tensorflow https://www.youtube.com/watch?v=PnK1jO2kXOQ&t=884s

step 2:Instal keras tensorflow https://github.com/jeffheaton/t81_558_deep_learning/tree/master/install

step 3:Instal all additional libraries

step 4:Prepare dataset , put files(=number of classes) with images to your working directory the code will label the three different classes and prepare the input for the network.

step 5:Model(Convolutional Neural Network) , Choose ,Train, Evaluate.


# Poacher_Detection_CNN
Poacher detection with 3 classes.

Classes 3: 2-Poachers with guns, 1-Poachers with arrows, 0-No Poachers.

The keras model accieved 90% accuracy in 20 epochs

The images collected manualy resized to 224x224 (3collors) and augmented.
