# Video-SuperResolution_And_GAN_FakeImageDetection

This project contains code for **Video Super Resolution** and **GAN generated fake image detection using super resolution**. The details for each of the project can be found in the *README* of corresponding folders.

## Contents

### Video Super Resolution

This is a project to apply image super resolution concept, by using SRCNN model, to the domain of video by breaking and merging frames of the video (detailed explianation in the **SRCNN** folder). 

### GAN fake image detection

**General Adversarial Networks** are capable of creating fake images with fake attributes such as nose, lips, eyebrows, etc., after being trained on real image data. This can be a hazard to systems that depend on face detection. The GAN generated images have a fingerprint as per the paper **Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints [link](https://arxiv.org/abs/1811.08180)** which was analysed for the super resolved versions of the fake images. The comparison of both fingerprints helped us detect the fake images with better confidence. 

The code will be uploaded in coming days.
