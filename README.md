Pistachio Image Denoising using Autoencoder and U-Net
Project Overview

This project focuses on image denoising using deep learning, aiming to restore clean pistachio images corrupted by Gaussian noise (μ = 0.0, σ = 0.1).
A Convolutional Autoencoder serves as the Baseline Model, while a U-Net Autoencoder is implemented as an enhanced model to achieve higher reconstruction quality.
Model performance is measured using the Structural Similarity Index (SSIM).

Model Architecture

Baseline Model: Convolutional Autoencoder with symmetric encoder-decoder structure.

U-Net Model: Skip-connected Autoencoder (U-Net) for better spatial feature preservation.

Model Performance
Comparison	Average SSIM
Noisy Input vs Clean Target	0.2787
Baseline Autoencoder vs Clean Target	0.9536
U-Net Autoencoder vs Clean Target	0.9755

The results show that both models successfully removed noise, with U-Net outperforming the Baseline by achieving a higher SSIM score.
This demonstrates that the U-Net architecture effectively preserves texture and fine image details during reconstruction.

Tech Stack

Python, TensorFlow / Keras

NumPy, Matplotlib, Pandas

scikit-image for SSIM computation

Google Colab for training and evaluation
