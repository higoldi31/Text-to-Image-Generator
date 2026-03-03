# 🎨 Fast Text-to-Image Generator using Stable Diffusion

A high-performance AI-powered Text-to-Image Generator built using Stable Diffusion Turbo, PyTorch, and Gradio.  
This project generates images from natural language prompts in near real-time using GPU acceleration.

---

## 🚀 Features

- 🧠 Stable Diffusion Turbo model
- ⚡ Fast image generation (1–5 seconds on GPU)
- 🎯 Optimized inference (4 steps)
- 💾 FP16 precision for performance
- 🌐 Simple and interactive Gradio UI
- ☁️ Deployable on Hugging Face Spaces

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Diffusers
- Gradio
- CUDA (GPU acceleration)
- xformers (memory-efficient attention)

---

## 🧠 How It Works

1. User enters a text prompt.
2. Prompt is converted into embeddings using a text encoder.
3. Random noise is initialized in latent space.
4. UNet model predicts noise iteratively.
5. Noise is removed in 4 inference steps.
6. Latent representation is decoded into an image.
7. Generated image is displayed via Gradio interface.

The model performs diffusion in latent space for computational efficiency.

---

