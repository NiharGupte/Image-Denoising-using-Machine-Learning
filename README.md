# Image-Denoising-using-Machine-Learning

The jupyter notebook contains code for denoising images using a patch based approach. Initially, clean images are taken and these images are artificially degraded with gaussian blurring and gaussian noise. Patches of size WxW are extracted from each of these images, and the labels of these patches are the initial clean central pixel. The patch is flattened out, and is provided as an input to the model, and three regression outputs are obtained (R, G, B pixel values). FCNN (Fully Connected Neural Network) and Random Forest Regression is used. 

## Dataset used

* BSD Dataset : [Link](https://www2.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/)

