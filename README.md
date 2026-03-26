# CNN Texture vs Shape Analysis

## Project Title

Do CNNs Really Understand Images or Just Textures? A Study Using Image Distortions

## Overview

This project investigates whether Convolutional Neural Networks (CNNs) truly understand object shapes or rely mainly on texture-based patterns.
A CNN model is trained on the Fashion-MNIST dataset and evaluated using different image distortions, including blur, noise, and edge-only representations.

## Objectives

* Train a CNN model for image classification
* Apply distortions (blur, noise, edge detection)
* Evaluate model performance under different conditions
* Analyse robustness and feature dependency
* Use confusion matrices for deeper evaluation

## Dataset

Fashion-MNIST dataset:
https://github.com/zalandoresearch/fashion-mnist

Contains 28x28 grayscale images across 10 clothing categories.

## Methods

* CNN model implemented using TensorFlow / PyTorch
* Training on original images only
* Testing on distorted images:

  * Gaussian blur
  * Additive noise
  * Edge-only images
* Evaluation using accuracy and confusion matrices

## Key Findings

* Highest accuracy on original images
* Moderate drop with blur
* Largest drop with noise
* Low performance on edge-only images (shape preserved, texture removed)
* CNN relies more on texture than shape

## How to Run

1. Install dependencies:
   pip install -r requirements.txt
2. Open the notebook
3. Run all cells

## Repository Contents

* Cnn Code_24154830.ipynb
* Cnn report_24154830.pdf
* README.md
* LICENSE
* requirements.txt

## Accessibility

* High-contrast visuals
* Clear labels and captions
* Structured layout

## Ethical Considerations

This work highlights limitations of CNNs in real-world scenarios. Models that rely heavily on texture may fail under blur, noise, or other distortions. This is important in applications such as healthcare, autonomous driving, and surveillance, where unreliable predictions may have serious consequences.

## Author

Anjaneya Indra Kowshik Repalle

## Licence

MIT License
