<div align="center">

# Zeyad Abdo

### AI Engineer · Building voice agents, computer vision pipelines, and multimodal systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zeyad-abdo-47826331b)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:imzeyad2005@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-1A3A5C?style=for-the-badge&logo=googledrive&logoColor=white)](https://docs.google.com/document/d/1Q5y_xUZ-SbqlGM8o2s4kyYX9ESdcP6ak/edit?usp=sharing&ouid=111629198194440248207&rtpof=true&sd=true)

</div>

---

## About

AI Engineer based in Egypt, finishing a BSc in Artificial Intelligence at Menoufia University. I build systems that ship — real-time voice pipelines, OCR pipelines for Arabic documents, and multimodal models written from scratch rather than pulled off a shelf.

- Working in **real-time voice AI**, **computer vision**, and **retrieval-augmented systems**
- Most of my recent work targets **Arabic-language use cases** that off-the-shelf models handle badly
- Volunteer **Data Analysis Instructor** at **IEEE Cairo University Student Branch**
- Co-founder at [**BrokenTreeStudio**](https://github.com/BrokenTree-Studio), an indie game studio *(side project)*
- Open to **Junior AI / ML Engineer** roles — remote or Egypt-based

---

## Featured Work

### 🎙️ [AI Call-Center Assistant](https://github.com/CUBeis/Ai-Call-Assistant) — *Real-time voice AI for Egyptian Arabic*

A live voice agent that listens to call-center agents in Egyptian Arabic, retrieves grounded answers from an internal knowledge base, and coaches them back in natural colloquial speech — under 3 seconds end to end, entirely in the browser.

```
Deepgram nova-3 (ar-EG)  →  FAISS + multilingual-e5  →  Llama-3.1-8B (NVIDIA NIM)  →  edge-tts
```

**Pipecat · WebRTC · Deepgram · FAISS · Llama 3.1 · Whisper fallback · Docker · CI**

> Runs without a telephony account, swaps STT/TTS providers via env vars, and defaults to free tiers.

---

### 🪪 [Egyptian National ID OCR](https://github.com/CUBeis/Egyptian-Id-OCR) — *Multi-stage document AI pipeline*

Detects, extracts, and validates Egyptian national ID cards. Three custom-trained YOLOv8 models handle card detection, field localization, and digit recognition, backed by a three-engine OCR ensemble for Arabic text. Decodes birth date, governorate, and gender straight from the 14-digit national number.

**YOLOv8 · TrOCR · PaddleOCR · EasyOCR · Streamlit · SQLite**

> Batch processing, real-time folder watching, confidence scoring, demographic analytics dashboard, Excel export.

---

### 🧭 [RepoPilot](https://github.com/CUBeis/RepoPilot) — *Agentic codebase analysis backend*

Structured repository analysis with retrieval and deterministic planning, so you can understand an unfamiliar project without opening forty files. Built API-first with a demo mode that runs without any API keys.

**FastAPI · Streamlit · Pytest · Ruff · optional OpenAI / OpenRouter**

> `438 tests passing` · clean Ruff · secrets kept out of the repo by design.

---

### 👁️ [Visual Question Answering System](https://github.com/CUBeis/VQA-System) — *Multimodal architecture built from scratch*

No pretrained backbones, no `nn.MultiheadAttention`. A custom ResNet CNN with squeeze-excitation and spatial attention produces 512×7×7 feature maps; a hand-written 4-layer Transformer encodes the question; cross-attention lets the question query the image so spatial grounding survives the fusion.

**PyTorch · custom Transformer · cross-attention · FastAPI · VQA v2.0 / MS-COCO**

> *The question defines what to look for; the image provides where to look.*

---

## Tech Stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=flat-square&logo=yolo&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**LLM & Retrieval**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![LangChain](https://img.shields.io/badge/RAG-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-13EF93?style=flat-square&logo=deepgram&logoColor=black)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Web**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

---

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=CUBeis&hide_border=true&background=00000000&stroke=30363D&ring=58A6FF&fire=58A6FF&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=58A6FF&sideLabels=8B949E&dates=6E7681">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=CUBeis&hide_border=true&background=00000000&stroke=D0D7DE&ring=1A3A5C&fire=1A3A5C&currStreakNum=1F2328&sideNums=1F2328&currStreakLabel=1A3A5C&sideLabels=57606A&dates=6E7681">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=CUBeis&bg_color=00000000&color=C9D1D9&title_color=58A6FF&line=58A6FF&point=58A6FF&area=true&area_color=58A6FF&hide_border=true">
  <img alt="Contribution graph" src="https://github-readme-activity-graph.vercel.app/graph?username=CUBeis&bg_color=00000000&color=1F2328&title_color=1A3A5C&line=1A3A5C&point=1A3A5C&area=true&area_color=1A3A5C&hide_border=true">
</picture>

</div>

---

## Contact

Actively looking for **Junior AI / ML Engineer** roles. I reply fast.

| | |
|---|---|
| **Email** | [imzeyad2005@gmail.com](mailto:imzeyad2005@gmail.com) |
| **LinkedIn** | [zeyad-abdo](https://linkedin.com/in/zeyad-abdo-47826331b) |
| **Location** | Menoufia, Egypt · open to remote |
