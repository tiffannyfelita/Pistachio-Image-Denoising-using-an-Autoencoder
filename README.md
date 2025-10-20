Pistachio Image Denoising using Autoencoder and U-Net
📘 Project Overview

This project focuses on image denoising using deep learning to restore clean pistachio images corrupted by Gaussian noise (μ = 0.0, σ = 0.1).
A Convolutional Autoencoder is used as the Baseline Model, while a U-Net Autoencoder is implemented as an enhanced model to achieve higher reconstruction quality.
Model performance is evaluated using the Structural Similarity Index (SSIM).

🧠 Model Architecture

Baseline Model: Convolutional Autoencoder with a symmetric encoder-decoder structure.

U-Net Model: Skip-connected Autoencoder (U-Net) for better spatial feature preservation.

📊 Model Performance Comparison
Model	SSIM (vs Clean Target)
Noisy Input	0.2787
Baseline Autoencoder	0.9536
U-Net Autoencoder	0.9755

✅ The U-Net Autoencoder outperforms the baseline by achieving a higher SSIM score, effectively preserving texture and fine image details during reconstruction.

🧰 Tech Stack

Languages & Frameworks: Python, TensorFlow / Keras

Libraries: NumPy, Matplotlib, Pandas, scikit-image

Environment: Google Colab
