# ``img2txt``
Generate a text description of an image using deep neural networks.

[Overview](#overview)

[Acknowledgements](#acknowledgements)

## Overview

The model architecture is based on

> "Show and Tell: Lessons learned from the 2015 MSCOCO Image Captioning
Challenge."
> Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan.
> *IEEE transactions on pattern analysis and machine intelligence (2016).*
> http://arxiv.org/abs/1609.06647

but the code is written from scratch using TensorFlow APIs.


## Requirements

### Library
``img2txt`` is developed on the following environment.
* Ubuntu 16.04.2 LTS
* Python 3.6
* NumPy
* TensorFlow 1.2
* Pillow
* NLTK (NLTK data not needed)
* Flask (for web UI)

### Datasets
* PASCAL


### Pre-trained models
* Copy Keras' pretrained model ~/.keras/models/vgg16_weights_tf_dim_ordering_tf_kernels.h5 to in img2txt/pretrained/vgg16_weights.h5.

## Acknowledgements
