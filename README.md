# 🧠 Mental Image Reconstruction from Human Brain Activity

This project focuses on reconstructing visual imagery directly from human brain activity using advanced neural decoding techniques and generative AI models like VQGAN-CLIP.

## 📌 Overview

The system leverages fMRI brain scan data and a pre-trained VQGAN+CLIP model to reconstruct mental images perceived or imagined by individuals. It follows a two-stage approach:
1. **Neural Decoding** – Map brain activity (from fMRI) to latent space features.
2. **Image Generation** – Use VQGAN-CLIP to generate corresponding images from the decoded features.

## 🧪 Project Workflow

- Load and preprocess fMRI dataset
- Train neural decoding models to map brain activity to CLIP embedding space
- Use VQGAN-CLIP to synthesize images from predicted embeddings

## 🧰 Tech Stack

- Python, NumPy, PyTorch
- VQGAN + CLIP
- Matplotlib, PIL for visualization
- fMRI datasets from publicly available sources (e.g., [NSD](https://www.natural-scenes-dataset.org/))

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/akankshar-oy/mental-image-reconstruction.git
cd mental-image-reconstruction
```

### Install Dependencies
Create a virtual environment and install requirements:
```bash
pip install -r requirements.txt
```

### Run the Notebook
Open the Jupyter or Colab notebook:
```bash
jupyter notebook Mental_image_reconstruction_colab.ipynb
```

