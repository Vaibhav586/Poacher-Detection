It should work in any compatable python version ( python 3.8.5 )

You could run TensorFlow for CPU Only ( or/and GPU)

kaggle repository image dataset and .npy files https://www.kaggle.com/georgiosgiouvanis/poacher-detection-3classes

Version Used

python : 3.8.5

numpy : 1.18.5

Keras : 2.4.0

tensorflow : 2.3.0

step 1: Create virstual inviroment virtual environment. Install miniconda+keras tensorflow https://www.youtube.com/watch?v=PnK1jO2kXOQ&t=884s

step 2:Instal keras tensorflow https://github.com/jeffheaton/t81_558_deep_learning/tree/master/install

step 3:Instal all additional libraries



# Poacher_Detection_CNN
Poacher detection with 3 classes.

Classes 3: 2-Poachers with guns, 1-Poachers with arrows, 0-No Poachers.

The keras model accieved 90% accuracy in 20 epochs

The images collected manualy resized to (224,224,3) and augmented.
