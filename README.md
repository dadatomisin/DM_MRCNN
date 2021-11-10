# DM_MRCNN
Train a Mask R-CNN with and without an added layer adding feature noise to the output of the backbone.
Feature noise is added by multiplying each element of tensors in the ordered dict by a number from the uniform random distribution between 0.8 and 1.2.
In this repo figures folder contains resulting figures. Code is run on google colab so when loading models ensure dict has been uploaded to colab directory.
Saved model dicts available at 
