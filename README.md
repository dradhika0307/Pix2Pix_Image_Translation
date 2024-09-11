Pix2Pix GAN for Image-to-Image Translation on the New York Facade Database
Overview
This project implements the Pix2Pix GAN architecture for translating architectural label images into realistic building facades. Using the New York Facade Database with 1096 images (256x256 pixels), the model produces high-quality image translations.

Features
Generator: U-Net-based architecture for enhancing image resolution and detail.
Discriminator: PatchGAN to classify image patches as real or generated.
Optimization: Hyperparameter tuning, Dropout, and Batch Normalization for improved model performance.
Evaluation: Model evaluated using Mean Squared Error (MSE) and Structural Similarity Index Measure (SSIM).
Requirements
TensorFlow
Python 3.x
Numpy
Matplotlib
Usage
Load the dataset and preprocess images (resize, random jittering, and normalization).
Train the model using the provided script.
Monitor training via TensorBoard and view generated results after 1k steps.
Results
The model generates realistic facade images with improved visual quality, optimized through hyperparameter tuning.
