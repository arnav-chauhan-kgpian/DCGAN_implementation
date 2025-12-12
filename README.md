# Deep Convolutional GAN (DCGAN)

A from-scratch implementation of a Deep Convolutional Generative Adversarial Network.

📌 Overview

This repository contains a clean, fully scratch-built implementation of a Deep Convolutional GAN (DCGAN) based on the original DCGAN paper https://arxiv.org/abs/1511.06434 . The goal of this project is to explore GAN training dynamics, stability tricks, and convolutional architectures by directly implementing the Generator and Discriminator without relying on high-level GAN toolkits.

The model learns to generate realistic images from random noise using adversarial training, where:

The Generator synthesizes fake images.

The Discriminator distinguishes real images from generated ones.

Both networks improve iteratively in a competitive learning setup.

🚀 Key Features

🔧 Pure From-Scratch Implementation
No GAN wrappers, only core TensorFlow/Keras layers to ensure full transparency in how DCGANs work.

📈 Training Progress Visualization
The model logs and saves generated images at regular intervals, making it easy to observe progressive feature learning.

💻 Kaggle-Optimized Workflow
Developed and trained on Kaggle GPU (Tesla P100) with minor environmental adjustments for compatibility.

🖼️ Training Results

Although Kaggle encountered a versioning clash that prevented logging the entire final execution output, image snapshots were saved successfully.

Images were generated every 30 epochs over 300 total epochs.

The checkpoints demonstrate clear convergence as the generator learns finer details.

Total training time: ~12 hours on Kaggle P100 GPU.

You can find the progression images inside the project folder.

🛠️ Tech Stack

Python

TensorFlow / Keras

Kaggle Kernels

👤 Author

Created with ❤️ by Arnav Chauhan
