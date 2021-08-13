# SRCNN

This project is a modified version of the code given in this [link](https://github.com/sdv4/SRCNN). The code is based on the theory given in the paper named
**Image Super-Resolution Using Deep Convolutional Networks ([link](https://ieeexplore.ieee.org/abstract/document/7115171))**. The code uses SRCNN model for image super resolution, which we modified
to use for Video Super Resolution.

**Image Super Resolution** in simple terms is to create a better resolution image from a poorer one i.e. to create pixel values that do not exist from the input image for the pixel created when upscaling the image to say 3x. **Video Super Resolution** is to use the same concept in terms of video files.

## Content

The files and their usages are:
1. train.ipynb: to train the model on the dataset
2. build.ipynb: to break the input video to frames, super-resolve it and merge it to form a video using ffmpeg tool.
3. evaluate.ipynb: a file to evaluate the benefit of using SRCNN than simple bicubic interpolation in terms of PSNR (Peak signal to noise ratio).
4. input.avi: input video
5. output.avi: output video

#### Disclaimer
We give proper credit to the original project as mentioned above and claim our work to be a modified version only.
