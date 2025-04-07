# Generative AI - Theory & Applications
## Author: Syed Abraham Ahmed
## NOTE: This is for portfolio purposes, please do not redistribute
This repository contains coursework for the course **Generative AI: Theory and Applications**. The reports focus on developing and evaluating a range of generative models—including Variational Autoencoders (VAEs), Generative Adversarial Networks (GANs), Diffusion Models, and evaluation metrics using Fréchet Inception Distance score, and Inception Score to evaluate and address tasks such as image inpainting, latent space interpolation, and unsupervised generation.

## Overview

The projects in this repo demonstrate:
- **Variational Autoencoders (VAEs):** Experiments with architecture modifications, latent space dimensionality adjustments, and custom loss functions (using DKL-divergence and Jensen Shannon Divergence for regularization) to improve reconstruction quality and generative performance. As well as implementations of latent space interpolation and t-SNE visualizations to assess the continuity and smoothness of learned representations.

- **Generative Adversarial Networks (GANs):** Comparative studies of DCGAN and WGAN-GP models, including analysis of training stability and sample quality using metrics like binary cross-entropy and Wasserstein loss (with gradient penalty).

- **Diffusion Models & Evaluation Metrics** Analysis of Diffusion Models, use of Fréchet Inception Distance and Inception Score as evaluation metrics of generated images.

- **LSTMs, GPT, and Transformers:** LSTM-based text generation, and Transformer-based approaches with analysis of Multihead Attention blocks.

## Repository Structure

```plaintext
├── reports/
|    ├── Syed_Ahmed_REPORT_1_VAE1.pdf # Report on Variational Autoencoders (Architecture Analysis)
|    ├── Syed_Ahmed_REPORT_2_VAE2.pdf # Report on Variational Autoencoders (General Comparison)
|    └── Syed_Ahmed_REPORT_3_GANs.pdf # Report on Generative Adversarial Networks (Performance and Analysis)
├── code/
│   └── requirements.txt         # Required Python packages and dependencies
├── assets/
|   └── image1.jpeg
└── README.md                    # This file
```
