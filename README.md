# Screenplay GPT-2 Fine-Tuning (Local, No APIs)

This project fine-tunes **GPT-2 Medium (355M)** on screenplay-style datasets to generate cinematic text: dialogues, scene directions, and professional screenplay formatting. Everything runs **locally on AMD GPUs (ROCm)** without external APIs.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)
![ROCm](https://img.shields.io/badge/AMD-ROCm-red)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## 🚀 Features

- **Local Execution**: Complete offline fine-tuning and inference
- **AMD GPU Support**: Optimized for ROCm stack (RX 6700 XT tested)
- **Screenplay Specialization**: Fine-tuned on diverse screenplay datasets
- **Efficient Training**: Support for mixed precision (FP16) and gradient checkpointing
- **Web Interface**: Local FastAPI server with interactive frontend
- **Monitoring**: Integrated TensorBoard logging for training metrics
- **Formatted Output**: Proper screenplay formatting with industry-standard elements

