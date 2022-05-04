<h1 align="center">
  Pansharpening of remote sensing images by Deep Learning
</h1>

DoseGAN is an architecture that is designed for medical images. In this architecture besides the U-Net architecture as the generator of GAN, they apply attention mechanism by some attention gates that consider the details of images better so we used this architecture for remote sensing images to output high-resolution images. This model is an image to image translation and it is based on the pix2pix model. We use this model aiming to get a better result in the pansharpening task for remote sensing images.

## References
<a id="1">[1]</a> 
V. Kearney, J. Chan, T. Wang, A. Perry, M. Descovich, O. Morin, S. Yom, and T. Solberg (2020). 
DoseGAN: a generative adversarial network for synthetic dose prediction using attention-gated discrimination and generation, 11073.

<a id="1">[2]</a> 
P. Isola, J.-Y. Zhu, T. Zhou, and A. A. Efros (2021). 
Image-to-Image Translation with Conditional Adversarial Networks.

<a id="1">[3]</a> 
W. Ma, Z. Pan, F. Yuan, and B. Lei (2019). 
Super-Resolution of Remote Sensing Images via a Dense Residual Generative Adversarial Network.
