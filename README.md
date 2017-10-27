## Progressive Growing of GANs for Improved Quality, Stability, and Variation
**Tero Karras** (NVIDIA), **Timo Aila** (NVIDIA), **Samuli Laine** (NVIDIA), **Jaakko Lehtinen** (NVIDIA and Aalto University)

![Representative image](https://raw.githubusercontent.com/tkarras/progressive_growing_of_gans/master/representative_image_512x256.png)

*We describe a new training methodology for generative adversarial networks. The key idea is to grow both the generator and discriminator progressively, starting from low-resolution images, and add new layers that deal with higher resolution details as the training progresses. This greatly stabilizes the training and allows us to produce images of unprecedented quality, e.g., CelebA images at 1024� resolution. We also propose a simple way to increase the variation in generated images, and achieve a record inception score of 8:80 in unsupervised CIFAR10. Additionally, we describe several small implementation details that are important for discouraging unhealthy competition between the generator and discriminator. Finally, we suggest a new metric for evaluating GAN results, both in terms of image quality and variation. As an additional contribution we construct a higher quality version of the CelebA dataset that allows meaningful exploration up to the resolution of 1024� pixels.*

## Links

* [Paper (high-quality version)](https://research.nvidia.com/publication/TODO)
* [Paper (arXiv version)](https://arxiv.org/abs/TODO)
* [Result video](https://youtu.be/TODO)
* [Pre-trained networks and image dumps](https://drive.google.com/open?id=0B4qLcYyJmiz0NHFULTdYc05lX0U)
* Datasets (not available at the moment)

## License

The source code is available under the CC BY-NC license:

```
# Copyright (c) 2017, NVIDIA CORPORATION. All rights reserved.
#
# This work is licensed under the Creative Commons Attribution-NonCommercial
# 4.0 International License. To view a copy of this license, visit
# http://creativecommons.org/licenses/by-nc/4.0/ or send a letter to
# Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
```

## Compatibility

We have tested the implementation using the following system configuration:

* NVIDIA DGX-1 with Tesla P100
* BaseOS 2.1.0, 4.4.0-92-generic kernel
* NVIDIA 384.81 driver
* Bleeding-edge version of Theano and Lasagne from Oct 17, 2017

We are planning to implement TensorFlow support in the near future.