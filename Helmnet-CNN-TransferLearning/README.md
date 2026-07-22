# HelmNet — Safety Helmet Detection

## Problem Statement
Classify images to detect whether individuals are wearing safety helmets, supporting automated workplace safety compliance monitoring.

## Approach
Compared four architectures: a custom CNN built from scratch, a VGG-16 base model, VGG-16 with a custom feedforward classification head, and the same with data augmentation. Used transfer learning (frozen VGG-16 base) to leverage pretrained ImageNet features on a small dataset (631 images), and applied augmentation, Dropout, Batch Normalization, and EarlyStopping to control overfitting.

## Skills
CNN architecture design, transfer learning, data augmentation, regularization, image preprocessing (OpenCV)

## Tech Stack
Python, TensorFlow, Keras, OpenCV, NumPy, Matplotlib, Seaborn

## Dataset
631 images across helmet/no-helmet classes. Raw images not included in this repo due to size and dataset licensing.
