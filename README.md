# DDPM — Denoising Diffusion Probabilistic Model for Face Generation

A complete implementation of a Denoising Diffusion Probabilistic Model (DDPM) trained on CelebA-HQ to generate human faces from pure Gaussian noise. Built entirely from scratch using PyTorch — no pretrained diffusion pipelines.

---

## Demo

🤗 Live Demo: [Hugging Face Spaces](https://huggingface.co/spaces/yourusername/ddpm-face-generator)  
📖 Technical Blog: [Medium](https://medium.com/@yourusername/ddpm-face-generation)

---

## Results

| Stage | Description |
|---|---|
| Forward Diffusion | Progressive noising over 500 timesteps |
| Reverse Diffusion | DDIM sampling in 200 steps |
| Output Resolution | 64×64 |
| Dataset | CelebA-HQ 256 (10,000 training images) |

---

## Architecture

Time-conditioned U-Net with the following structure:
