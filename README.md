# The effects of the sharpening and blurring of image edges on the 
performance and biases of CNNs

This repository contains the scripts used to generate data, train models, and evaluate models to determine the accuracy and shape texture bias implications of the sharpening and blurring of image edges in training data of semantic segmenation model. Note that due to the size of the data files, they are excluded from this repository.

CONTENTS OF THIS REPOSITORY
---------------------

 * edge_blurring.py
This script generates a cityscapes training dataset with the edges of the shapes within the images blurred.

 * edge_sharpening.py
This script generates a cityscapes training dataset with the edges of the shapes within the images sharpened.

 * results.py
This script contains a variety of functions to evaluate and display results on both accuracy and shape texture bias of each model.

 * segmentation_model.py
This file contains the script for training any of the blurred, sharpened, or standard dataset models. The basis for this model can be found in the following tutorial: https://www.youtube.com/watch?v=hWN1Xqu8aRE. 
 
 * utils.py
This file contains multiple helper functions
