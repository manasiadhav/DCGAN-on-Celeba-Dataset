# DCGAN-on-Celeba-Dataset
Overview

This repository contains the implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) trained on the CelebA (CelebFaces Attributes) dataset to generate realistic human face images. The model is implemented using PyTorch and follows best practices for GAN training.

Dataset

The model is trained on the CelebA dataset, which consists of over 200,000 celebrity face images.

The dataset is loaded from Kaggle using kagglehub and stored in /kaggle/input/celeba-dataset/img_align_celeba.

Images are resized to 64x64 pixels and normalized for stable GAN for training stability.

Normalize images to [-1, 1]
