# SRGAN Image Super Resolution

PyTorch implementation of SRGAN for single image super-resolution using:

- Residual blocks
- Adversarial training
- Multi-layer VGG perceptual loss
- Bicubic comparison
- PSNR and SSIM evaluation

## Features

- SRGAN implementation
- Google Colab support
- Training and validation curves
- SRGAN vs Bicubic comparison
- Publication-style visualization

## Results

| Bicubic | SRGAN | Ground Truth |
|---|---|---|
| image | image | image |

## Training

- Dataset: DIV2K
- Upscale factor: 4x
- Loss:
  - adversarial loss
  - perceptual loss
- Framework: PyTorch

## Run

```bash
pip install -r requirements.txt
python train.py
