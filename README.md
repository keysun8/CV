# CV

from pathlib import Path

readme = r"""<div align="center">

# Kishan Madlani

### Computer Vision Research Engineer | Generative AI

Building generative models, diffusion systems, and multimodal AI applications.

[Email](mailto:kishanmadlani08@gmail.com) · [LinkedIn](#) · [GitHub](https://github.com/keysun8) · [Hugging Face](#)

</div>

---

## About

Computer Vision Research Engineer specializing in generative and multimodal AI, with hands-on experience building diffusion models from scratch, text-conditioned image generation, and synthetic-data pipelines. Research experience includes latent diffusion, multimodal learning, metric learning, and LLM/RAG systems, with interests in generative modeling, vision-language models (VLMs), and efficient AI.

## Experience

### Computer Vision Research Engineer — CVIT Lab, IIIT Hyderabad
*Hyderabad, Telangana · February 2026 – August 2026*

- Built a diffusion-based model that generates realistic Hindi handwriting in real writers' styles.
- Used the model to create a fully synthetic dataset; combining synthetic and real data improved OCR accuracy by **17%** over real-only training.
- Work documented in a technical report.

## Selected Projects

### 1. Diffusion-Based Handwriting Generation
**Technologies:** Diffusion Models · Proxy-NCA Metric Learning · PyTorch

- Built and trained a Stable Diffusion-style latent diffusion model from scratch, featuring a custom U-Net, dual MobileNetV2-style/content encoders, and a cross-attention blender.
- Generated realistic Hindi handwriting in a target writer's style from arbitrary input text.
- Trained on **900 writers** and **25K+ samples** using a **270M-parameter** model.
- Achieved **FID 17.0** and **HWD 0.97**.
- Used Proxy-NCA metric learning and row/column masking to disentangle writer identity from text content.

**Links:** [GitHub](https://github.com/keysun8/Diffusion_HW_Hindi) · [Hugging Face demo](#) · [Google Colab GPU demo](#)

### 2. Diffusion-Based Face Image Generation
**Technologies:** PyTorch · Diffusion Models · Latent Space · Image Generation

- Developed an unconditional face-image generation model by training a U-Net-based latent diffusion model from scratch on the CelebA dataset.
- Achieved a **Fréchet Inception Distance (FID) of 12.0**, demonstrating high-fidelity and diverse synthetic face generation.
- Built a **135M-parameter** model using a standard DDPM noise schedule in a pretrained VAE's compressed latent space to reduce compute compared with pixel-space diffusion.

**Links:** [GitHub](#) · [Hugging Face demo](#)

### 3. RAG-Based YouTube Video Chatbot
**Technologies:** RAG · FAISS · Pinecone · LangChain · Python · LLMs

- Built a RAG-based chatbot that enables natural-language interaction with YouTube videos using their transcripts.
- Implemented vector retrieval using FAISS and Pinecone, combining retrieved context with an LLM for grounded responses.
- Deployed the chatbot on a university Discord server, processing **500+ queries from 47+ users**.

**Link:** [GitHub](#)

## Technical Skills

- **Languages:** Python, Java
- **Deep Learning Frameworks:** PyTorch, TensorFlow
- **Computer Vision:** OpenCV, image processing, feature extraction, CNNs, Vision Transformers (ViTs), object detection, image generation
- **Generative AI:** GANs, VAEs, diffusion models, latent diffusion
- **LLM / Multimodal AI:** LLMs, Retrieval-Augmented Generation (RAG), LangChain, LangGraph
- **Tools:** Git, Linux, Weights & Biases (W&B), Optuna

## Education

### Sardar Vallabhbhai National Institute of Technology (NIT Surat)
**M.Sc. (Integrated) in Physics** · December 2021 – June 2026  
Surat, India

- **Thesis:** *Image Generation: Diffusion-Based Models*, under Prof. C. V. Jawahar
- **Relevant coursework:** Machine Learning, Statistics, Linear Algebra, Computer Vision, Python

---

## Contact

- **Email:** [kishanmadlani08@gmail.com](mailto:kishanmadlani08@gmail.com)
- **GitHub:** [keysun8](https://github.com/keysun8)

> **Before publishing:** Replace the `#` placeholders above with your actual LinkedIn, Hugging Face, demo, and project repository URLs. Confirm all dates and metrics are current.
"""

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created: {path}")
