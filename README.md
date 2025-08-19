# Screenplay GPT-2 Fine-Tuning (Local, No APIs)

This project fine-tunes **GPT-2 Medium (355M)** on screenplay-style datasets to generate cinematic text:  
dialogues, scene directions, and professional screenplay formatting.  

Everything runs **locally on AMD GPUs (ROCm)** without external APIs.

---

## Features
- Fine-tuning GPT-2 Medium on screenplay datasets
- Dataset preprocessing (raw → cleaned → tokenized)
- Training pipeline with Hugging Face `transformers` + `accelerate`
- GPU acceleration via ROCm (`torch` built for AMD)
- Evaluation with perplexity + sample generations
- Local web app (FastAPI + frontend) for text generation
- TensorBoard logging & experiment tracking
- Organized repo structure for reproducibility