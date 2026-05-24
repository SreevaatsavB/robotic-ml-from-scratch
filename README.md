# Robotic ML — From Scratch

A personal learning repo where I implement robotics & embodied AI papers from scratch — understanding every component by building it, not just running it.

## Structure

```
ACT/
  autoencoders.ipynb      # AE, VAE, CVAE — core building blocks
  act_implementation.ipynb # Action Chunking with Transformers (Chi et al., 2023)
  ACT.pdf                  # Original paper
```

## Topics

- **Autoencoders** — AE → VAE → CVAE, with visual comparison of latent spaces, reconstructions, and generative sampling
- **ACT (Action Chunking with Transformers)** — CVAE + Transformer encoder/decoder for imitation learning; implements the full training and inference pipeline

## Stack

- Python 3.12
- PyTorch
- NumPy, Matplotlib, Seaborn

## Papers

- [Action Chunking with Transformers (ACT)](https://arxiv.org/abs/2304.13705) — Zhao et al., 2023
