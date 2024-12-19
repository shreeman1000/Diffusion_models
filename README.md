# Diffusion Models: DDPM, DDIM, and Score Matching

This repository contains a Jupyter Notebook implementing **Denoising Diffusion Probabilistic Models (DDPM)**, **Deterministic Diffusion Sampling (DDIM)**, and **Score Matching** techniques for generative modeling. These methods enable the generation of high-quality data samples through iterative denoising and efficient sampling.

## Features

### 1. **Denoising Diffusion Probabilistic Models (DDPM)**
- Implements the forward diffusion process with Gaussian noise addition.
- Trains a model to reverse the noise process and generate data samples.
- Includes visualization of the noise schedule and the generated samples.

### 2. **Deterministic Diffusion Sampling (DDIM)**
- Implements an efficient deterministic sampling method for generating high-quality outputs with fewer steps compared to DDPM.

### 3. **Score Matching**
- Incorporates score-based techniques to estimate gradients of the data distribution for efficient sampling and training.

Install them via pip:

```bash
pip install torch matplotlib numpy
