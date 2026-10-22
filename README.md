<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Kishan%20Madlani&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Computer%20Vision%20Research%20Engineer&descAlignY=58&descSize=22&animation=fadeIn" width="100%" alt="banner" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=36BCF7&center=true&vCenter=true&width=700&lines=Generative+%26+Multimodal+AI;Diffusion+Models+from+Scratch;Text-Conditioned+Image+Generation;Synthetic+Data+Pipelines;LLMs+%26+RAG+Systems" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/YOUR_GITHUB_USERNAME"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://huggingface.co/YOUR_HF_USERNAME"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/></a>
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/YOUR_LEETCODE_USERNAME"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
<a href="https://signal.org"><img src="https://img.shields.io/badge/Signal-keysun.89-3A76F0?style=for-the-badge&logo=signal&logoColor=white" alt="Signal"/></a>
<a href="mailto:kishanmadlani08@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&label=Profile%20Views&color=0e75b6&style=flat-square" alt="views"/>

</div>

---

## 👋 About Me

Computer Vision Research Engineer specializing in **generative and multimodal AI**, with hands-on experience building **diffusion models from scratch**, text-conditioned image generation, and **synthetic-data pipelines**.

My research spans **latent diffusion**, **multimodal learning**, **metric learning**, and **LLM/RAG systems**, with a keen interest in generative modeling, VLMs, and efficient AI.

<div align="center">

| 🔬 Focus | 🎓 Education | 📍 Location |
|:---:|:---:|:---:|
| Generative & Multimodal AI | M.Sc. (Integrated) Physics, NIT Surat | India |

</div>

---

## 💼 Experience

### 🧠 Computer Vision Research Engineer
**CVIT Lab, IIIT Hyderabad** &nbsp;|&nbsp; 📍 Hyderabad, Telangana &nbsp;|&nbsp; 🗓️ Feb 2026 – Aug 2026

- Built a **diffusion-based model** that generates realistic **Hindi handwriting** mimicking real writers' styles, and used it to create a **fully synthetic dataset**.
- Combining synthetic and real data improved **OCR accuracy by 17%** over real-only training. 📄 *[Tech Report]*

---

## 🚀 Projects

### ✍️ Diffusion-Based Handwriting Generation

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Diffusion](https://img.shields.io/badge/Diffusion%20Models-8A2BE2?style=flat-square)
![Metric Learning](https://img.shields.io/badge/Proxy--NCA-Metric%20Learning-informational?style=flat-square)

- Built and trained a **Stable Diffusion-style latent diffusion model from scratch** (custom UNet, dual MobileNetV2 style/content encoders, cross-attention Blender) to generate realistic Hindi handwriting in a target writer's style from arbitrary input text.
- Trained on **900 writers** and **25K+ samples** with a **270M-parameter** model.
- Achieved **FID 17.0** and **HWD 0.97** by designing a style encoder with **Proxy-NCA metric learning** and **column/row masking** to disentangle writer identity from text content.

<div align="center">

| 📊 FID | 📉 HWD | 🧮 Params | ✍️ Writers | 🗂️ Samples |
|:---:|:---:|:---:|:---:|:---:|
| **17.0** | **0.97** | **270M** | **900** | **25K+** |

</div>

<a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_HANDWRITING_REPO"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://huggingface.co/spaces/YOUR_HF_USERNAME/YOUR_HANDWRITING_SPACE"><img src="https://img.shields.io/badge/Demo-HF%20Space%20(CPU)-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
<a href="YOUR_COLAB_LINK"><img src="https://img.shields.io/badge/Demo-Colab%20(GPU)-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/></a>

---

### 🧑 Diffusion-Based Face Image Generation

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Diffusion](https://img.shields.io/badge/Latent%20Diffusion-8A2BE2?style=flat-square)
![Image Generation](https://img.shields.io/badge/Image%20Generation-0A66C2?style=flat-square)

- Trained an **unconditional UNet-based latent diffusion model from scratch** on **CelebA**, achieving **FID 12.0** with high-fidelity, diverse synthetic faces.
- **135M parameters**, standard **DDPM noise schedule**, trained in a pretrained **VAE's compressed latent space** to significantly reduce compute vs. pixel-space diffusion.

<div align="center">

| 📊 FID | 🧮 Params | 🗂️ Dataset |
|:---:|:---:|:---:|
| **12.0** | **135M** | **CelebA** |

</div>

<a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_FACE_REPO"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=for-the-badge&logo=github"/></a>
<a href="https://huggingface.co/spaces/YOUR_HF_USERNAME/YOUR_FACE_SPACE"><img src="https://img.shields.io/badge/Demo-HF%20Space-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>

---

### 🎬 RAG-Based YouTube Video Chatbot

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

- Built a **RAG chatbot** for natural-language interaction with YouTube videos using transcripts.
- Implemented a **vector retrieval pipeline** with **FAISS** and **Pinecone**, feeding retrieved context to an LLM for grounded responses.
- Deployed on a university **Discord** server: **500+ queries from 47+ users**.

<a href="https://github.com/YOUR_GITHUB_USERNAME/YOUR_RAG_REPO"><img src="https://img.shields.io/badge/Code-GitHub-181717?style=for-the-badge&logo=github"/></a>

---

## 🛠️ Technical Skills

<div align="center">

### 💻 Languages
<img src="https://skillicons.dev/icons?i=py,java&theme=dark" alt="languages"/>

### 🧠 Deep Learning Frameworks
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark" alt="dl frameworks"/>

### 👁️ Computer Vision
<img src="https://skillicons.dev/icons?i=opencv&theme=dark" alt="cv"/>

![Image Processing](https://img.shields.io/badge/Image%20Processing-5C3EE8?style=for-the-badge)
![CNNs](https://img.shields.io/badge/CNNs-0A66C2?style=for-the-badge)
![ViTs](https://img.shields.io/badge/Vision%20Transformers-FF6F00?style=for-the-badge)
![Object Detection](https://img.shields.io/badge/Object%20Detection-00A98F?style=for-the-badge)
![Feature Extraction](https://img.shields.io/badge/Feature%20Extraction-C2185B?style=for-the-badge)
![Image Generation](https://img.shields.io/badge/Image%20Generation-8A2BE2?style=for-the-badge)

### 🎨 Generative AI
![GANs](https://img.shields.io/badge/GANs-E91E63?style=for-the-badge)
![VAEs](https://img.shields.io/badge/VAEs-9C27B0?style=for-the-badge)
![Diffusion](https://img.shields.io/badge/Diffusion%20Models-673AB7?style=for-the-badge)
![Latent Diffusion](https://img.shields.io/badge/Latent%20Diffusion-3F51B5?style=for-the-badge)

### 🤖 LLM / Multimodal AI
![LLMs](https://img.shields.io/badge/LLMs-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2E7D32?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### 🧰 Tools
<img src="https://skillicons.dev/icons?i=git,github,linux,vscode&theme=dark" alt="tools"/>

![Weights & Biases](https://img.shields.io/badge/Weights%20&%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-2C6FBB?style=for-the-badge)

</div>

---

## 🎓 Education

**Sardar Vallabhbhai National Institute of Technology (NIT Surat)** — Surat, India
🎓 **M.Sc. (Integrated) Physics** &nbsp;|&nbsp; 🗓️ Dec 2021 – Jun 2026

- 📝 **Thesis:** *Image Generation: Diffusion-based Models* — under **Prof. C. V. Jawahar**
- 📚 **Coursework:** Machine Learning · Statistics · Linear Algebra · Computer Vision · Python

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="top langs"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" alt="streak"/>

</div>

---

## 📫 Let's Connect

<div align="center">

I'm open to collaborations and opportunities in **generative AI, diffusion models, and multimodal learning**.

<a href="mailto:kishanmadlani08@gmail.com"><img src="https://img.shields.io/badge/Email-kishanmadlani08%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://signal.org"><img src="https://img.shields.io/badge/Signal-keysun.89-3A76F0?style=for-the-badge&logo=signal&logoColor=white"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" alt="footer"/>

</div>
