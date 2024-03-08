# 🎨 Build an Image Style Transfer Tool using CycleGANs
### **Author : Roxanne Li**

## Mentee Information 📚
- **Name:** Iqbal Maulana Kholidi
- **Program:** IBM Advanced AI

## Overview 🌟
Artists like Claude Monet are recognized for the unique styles of their works, such as the unique colour scheme and brush strokes. These are hard to be imitated by normal people, and even for professional painters, it will not be easy to produce a painting whose style is Monet-esque. However, thanks to the invention of Generative Adversarial Networks (GANs) and their many variations, Data Scientists and Machine Learning Engineers can build and train deep learning models to bring an artist's peculiar style to your photos.

In this project, you will be guided through building a style transfer tool using CycleGAN to "translate" the photos in your album into paintings that are Monet-esque!

## Table of Contents 📑
1. Objectives
2. Setup
    - Installing Required Libraries
    - Importing Required Libraries
    - Defining Helper Functions
4. What is Image Style Transfer in Deep Learning?
5. CycleGANs
    - quick recap on vanilla GANs
    - What's novel about CycleGANs?
6. Data Loading
7. Building the Generator
    - Defining the Downsampling Block
    - Defining the Upsampling Block
    - Assembling the Generator
8. Building the Discriminator
9. Building the CycleGAN Model
10. Defining Loss Functions
11. Model Training
    - Training the CycleGAN
12. Visualize our Monet-esque photos
    - Loading the Pre-trained Weights
    - Visualizing Style Transfer Output

## Objectives 🎯
After completing this project you will be able to:

- Describe the novelty about CycleGANs
- Understand Cycle Consistency Loss
- Describe the complicated architecture of a CycleGAN
- Gain good practices of training deep learning models
- Implement a pre-trained CycleGAN for image style transfer
