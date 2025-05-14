## Project Overview
This project develops machine learning models to automatically distinguish between AI-generated images and authentic human-made images. We evaluate convolutional neural networks (CNNs) and transformer-based architectures on large-scale datasets to establish reliable detection methods.
With the rapid advancement of generative AI technologies like GPT-4o, distinguishing synthetic from authentic content has become critical for preventing deepfakes and misinformation and maintaining trust in digital media.

## Datasets

### Shutterstock-DeepMedia Dataset (Primary)

79,950 training images and 19,986 test images;
Balanced between real and AI-generated images;
Real images from Shutterstock; synthetic images from DeepMedia.


### CIFAKE Dataset (Generalization)

120,000 low-resolution images (32×32);
60,000 real images from CIFAR-10;
60,000 synthetic images from Stable Diffusion v1.4.



## Models Tested

ResNet50 - CNN architecture with residual connections

InceptionV3 - CNN with multi-scale feature extraction

EfficientNet-B0 - Efficient CNN architecture

Vision Transformer (ViT-B/16) - Transformer-based architecture

## Acknowledgments

Kaggle competition: Detect AI vs. Human-Generated Images

CIFAKE dataset by Bird & Lotfi
