# Sparse Autoencoder

## Arthur Ufongene 2025

### Summary
This repository is adapted from the ENGS 106 graduate class at Dartmouth. Initially designed to work on grayscale images, I adapted it to work on RGB image patches.

This sparse autoencoder is a neural network of linear layers, with a sparse second layer to encourage the model to store only important information. If you look at the parameter visualizations, you can see bright edges in each column of the parameters, signaling that the autoencoder is encoding edge detection information in its paramters.

Each branch experiments with different model architecture for best encoding edge detection in its layers and reconstructing inputs. They contain images of entry layer params, as well as original and reconstruted data. In the visualization of entry layer params, bright shapes signify the shape of edges that kernel is detecting. The color of the shapes indicate which channel (R,G, or B) that the kernel is detecting edges in.

### Conclusion

at
