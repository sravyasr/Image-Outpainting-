# Image-Outpainting-
This is an implementation of Painting Outside the Box: Image Outpainting paper from Standford University.Some changes have been made to work with 256*256 image:

- Added Identity loss i.e from generated image to the original image <br/>
- Removed patches from training data. (training pipeline) <br/>
- Replaced masking with cropping. (training pipeline) <br/>
- Added convolution layers.
