# Lightweight and Robust Reversible Image Steganography

##Overview
This project presents a **lightweight and reversible image steganography framework** combining:
- **Multi-Scale Convolution** for robustness to resolution changes.
- **Embedding Block** for compact feature representation of secret images.
- **Simplified UNet** for efficient reconstruction.
- **Invertible Neural Network**-based paths for accurate hiding and revealing.

The method ensures:
1. High visual quality of stego images.
2. Precise recovery of hidden images.
3. Resistance to steganalysis (CNN, SRNet).

---

## Architecture
- **Hiding Path:** Multi-Scale Convolution + Embedding Block to embed secret features into cover image.
- **Revealing Path:** Inverse network for secret image recovery.
- **Parallel multi-scale kernels:** 7×7, 5×5, 3×3 for better feature extraction.
- **Activation Variants:** Tested Sigmoid/ReLU combinations in hiding/revealing blocks.

---

## Key Results
- **Best Configuration**: Multi-Scale + UNet  
- **PSNR**: 27.0597 dB  
- **SSIM**: 0.9113  
- **Steganalysis Resistance**: CNN (~50% accuracy), SRNet (~73% accuracy)

You can download the dataset from Google Drive : [https://drive.google.com/file/d/1dojkKIqT9WKrwry0kUQPA2ckfy_dHZ7J/view?usp=sharing].

## Large Files
Experiments file : [https://drive.google.com/file/d/1VkcrQfroUFVuE0IbnCfrwF5cTDfveZwH/view?usp=sharing]

