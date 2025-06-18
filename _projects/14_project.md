---
layout: page
title: Cross-Person Virtual Try-On
description: Addressing the problem of person to person garment transfer using Diffusion Transformer 
img: assets/img/vton.png
importance: 1
category: Projects (UCSD)
---

<p align="justify"> Cross-Person Virtual Try-On | ECE285: Deep Generative Models | Prof. Pengtao Xie <br><br>
- Leveraged IDM-VITON preprocessing to generate dataset for cross person garment transfer along with DensePose segmentation
maps to convert VITON-HD images into cloth-agnostic and garment-conditioned token streams for diffusion-transformer training<br>
- Architected and implemented a 16-block Diffusion Transformer denoiser integrating self-attention on noise and cloth-agnostic
tokens, cross-attention on garment tokens, and FiLM-based timestep modulation for high-fidelity virtual try-on<br>
- Optimized the diffusion pipeline with noise-aware EDM parameterization, a 2nd ODE solver and CFG achieving an FID of 27.7
</p>


<a href = "https://docs.google.com/presentation/d/1FvhwY9p_9m8LnOp9rhZ8ZqvxGwA7lHnvmT-qCUaVKTU/edit?usp=sharing"> [Presentation]</a><a href = "https://jay6101.github.io/assets/pdf/ECE285_Final_report.pdf"> [Project Report]</a>