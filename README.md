# Project Title
English Alphanumeric Character Learning with Keras

# Overview
This repo contains a training script `chars74k_train.py` written using the Deep learning framework [Keras](http://www.keras.io) that trains a simple Deep convolutional neural network model on the [Chars 74k Image dataset](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/#download).
Please note that the training is done on part of the full dataset containing images with good quality (bad quality images are not used for training)
Running the script for 15 iterations yield 95.72% training and 81.64% validation accuracy. Conv-net weights after 15 iteratons is saved in `weights.best.hdf5`.

