# Sparse Autoencoder

## Arthur Ufongene 2025

This repository is adapted from the ENGS 106 graduate class at dartmouth.

This sparse autoencoder is a neural network of linear layers, with a sparse second layer to encourage the model to store only important information. The model has 1 encoding layer and 2 decoding layers, and it is designed to work on the CIFAR10 dataset. Functions are implemented to visualize the reconstruction of data, as well as parameters. If you look at the parameter visualizations, you can see bright edges in each column of the parameters, signaling that the autoencoder is encoding edge detection information in its paramters.
