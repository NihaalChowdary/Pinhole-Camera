# Pinhole Camera

A deep learning model developed using autoencoder architecture to enhance the clarity and quality of images taken from a pinhole-sized aperture.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Model Architecture](#model-architecture)


## Introduction

The Pinhole Camera project leverages the power of deep learning to address the challenges associated with capturing high-quality images through a pinhole-sized aperture. Traditional pinhole cameras, while simple and inexpensive, suffer from issues like low light sensitivity and poor image clarity due to the small aperture size. Our project aims to mitigate these issues using a sophisticated autoencoder architecture.

### Background

A pinhole camera works on the principle of light passing through a small aperture to form an image on the opposite side. However, the small aperture size limits the amount of light entering the camera, resulting in images that are often dark and lack detail. To improve the quality of these images, we use deep learning techniques to enhance the clarity and quality of images captured by a pinhole camera.

### Objective

The primary objective of this project is to develop a deep learning model that can take an image captured through a pinhole-sized aperture and enhance its quality to match that of an image captured through an aperture five times larger. By doing so, we aim to retain the simplicity and cost-effectiveness of pinhole cameras while significantly improving their image quality.

### Approach

To achieve this, we employ an autoencoder architecture. An autoencoder is a type of neural network that learns to compress and then reconstruct input data. In our case, the encoder compresses the low-quality pinhole image, and the decoder reconstructs it into a higher-quality image. The model is trained on a dataset of paired images: one taken through a pinhole-sized aperture and the other through a larger aperture. The training process involves minimizing the difference between the reconstructed images and the high-quality images.

### Significance

This approach has several potential applications:
- **Low-cost Photography:** Enhancing images from inexpensive pinhole cameras for educational or artistic purposes.
- **Historical Restoration:** Improving the quality of old photographs taken with primitive cameras.
- **Security:** Enhancing images from low-resolution security cameras for better identification and monitoring.

By advancing the capabilities of pinhole cameras through deep learning, this project bridges the gap between traditional photography techniques and modern computational photography.

## Features

- Autoencoder architecture for image enhancement
- Trained on images taken from a pinhole-sized aperture
- Improves image clarity and quality

## Model Architecture
![Architecture](https://github.com/NihaalChowdary/Pinhole-Camera/blob/fd111bc7813e90db48fd171fc9fc3f0f7a7b2887/A-convolutional-autoencoder-for-latent-enhancement.png)
