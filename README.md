# Image Generation

Image generation with Stable Diffusion and a custom DDPM implementation in PyTorch.

- Stable Diffusion inference with classifier-free guidance experiments.
- Unconditional and class-conditional DDPM on the two-moons dataset.
- Image super-resolution from 16×16 to 128×128 with a custom U-Net and a pretrained VAE.
- Evaluation using PSNR, SSIM and LPIPS, with comparisons across diffusion steps and against bicubic interpolation.

[Experiment report](experiments.pdf) — training curves and sample outputs.
