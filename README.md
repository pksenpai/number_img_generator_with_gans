# Numbers Generator
- Generate numbers with mnist dataset and tGAN, DCGAN, SGAN & CGAN models.
- Using Keras library & tensorflow backend.

----------------------------------------------------------------------------
## tGAN:
- using Dense layers.
- a basic model & the neighborhood of pixels is not considered.
- no feature extraction & no feature maps.

First Samples             |  Latest Samples
:-------------------------:|:-------------------------:
![](GAN/GAN_first_test_samples.png)  |  ![](GAN/GAN_latest_test_samples.png)

## DCGAN:
- using convolutional & deconvolutional layers.
- the neighborhood of pixels is considered.
- feature maps & depth.
- has a cleaner output.

First Samples             |  Latest Samples
:-------------------------:|:-------------------------:
![](DCGAN/DCGAN_first_test_samples.png)  |  ![](DCGAN/DCGAN_latest_test_samples.png)

## SGAN:
- Similar to DCGAN, but useing semi-supervised learning for the discriminator.
- model has a lighter & more accurate discriminator than DCGAN.

First Samples             |  Latest Samples
:-------------------------:|:-------------------------:
![](DCGAN/DCGAN_first_test_samples.png)  |  ![](DCGAN/DCGAN_latest_test_samples.png)

## CGAN:

First Samples             |  Latest Samples
:-------------------------:|:-------------------------:
![]()  |  ![]()

