# 🖼️ Text-to-Image Generation using Stable Diffusion

> Transform your imagination into stunning visuals — one prompt at a time.


## 🌟 Overview

This project implements a **state-of-the-art Text-to-Image Generation pipeline** powered by **Stable Diffusion**, built from scratch using **PyTorch** and **Hugging Face Diffusers**.  
It allows users to enter any descriptive text prompt and instantly generate high-quality, realistic images — all through an interactive **Gradio interface**.

---

## 🚀 Key Features

 **Stable Diffusion Integration** — Leverages advanced diffusion models for text-to-image synthesis.  
 **Multiple Schedulers Supported** — Euler, DDIM, DPM Solver, and more for varied generation quality.  
 **GPU Acceleration** — Harnesses CUDA and Xformers for ultra-fast inference.  
 **Interactive Web UI** — User-friendly Gradio app to input prompts and view results instantly.  
 **Customizable Settings** — Easily adjust image resolution, inference steps, and guidance scale.  
 **Memory Optimization** — Efficient GPU memory management with auto garbage collection.

---

## 🧠 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Core Framework** | PyTorch |
| **Model Hub** | Hugging Face Diffusers |
| **Schedulers** | Euler, DDIM, LMS, DPM |
| **UI Framework** | Gradio |
| **Utilities** | NumPy, Pillow, Matplotlib |
| **Acceleration** | CUDA, Xformers |
| **Language** | Python 3.10+ |

---

## ⚙️ Installation

```bash
# Clone this repository
git clone https://github.com/yourusername/text-to-image-generation.git
cd text-to-image-generation

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install diffusers==0.21.0 transformers==4.30.2 accelerate==0.20.3
pip install safetensors==0.3.1 xformers==0.0.20 Pillow==9.5.0
pip install numpy==1.24.4 matplotlib==3.7.2 gradio==4.0.0
