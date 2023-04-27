# SRCNN, Image Super-Resolution Using Deep Convolutional Networks in Tensorflow

**The algorithm is not mine**, its an implementation of the SRCNN introduced by [Dong et al](https://arxiv.org/pdf/1501.00092.pdf)

Welcome to the Image Super-Resolution Using Deep Convolutional Networks in Tensorflow project!

This is an implementation of the SRCNN algorithm introduced by Dong et al. I have provided a few functions to visualize the weights of the model (kernels) and the feature maps.

**Project Structure:**

- The model directory contains the pre-trained model which is trained on a single color channel, and hence expects this as an input.
- The srcnn.py is the main file where the network is initialized and tested on an image supplied in the "image" directory.
- The output directory contains the results obtained.

##To run the project, you need Python 3.7 and the following dependencies:

- MatPlotLib: for visualization
- NumPy: for everything, it's NumPy
- Tensorflow: the network is built using Tensorflow
- Scipy: for image processing
- Scikit-image: for computing PSNR.

Enjoy!
