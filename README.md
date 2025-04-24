# Image Captioning with BLIP + Gradio

Welcome to my image captioning web app, built using the powerful **BLIP model** from Salesforce and brought to life with **Gradio**. This project is part of my ongoing exploration of applying vision-language transformer models in real-world scenarios.

---

## What This App Does

This application takes any input image and generates a human-like caption describing it. It's powered by the `Salesforce/blip-image-captioning-base` model and uses Gradio to provide a clean, intuitive interface.

---

## Tech Stack

- **Python 3.10**
- **Gradio** – For building an interactive web UI
- **Transformers (Hugging Face)** – For model access and inference
- **Pillow (PIL)** – For image preprocessing
- **NumPy** – For converting and handling image arrays

---

## Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/yourusername/image-captioning-app.git
cd image-captioning-app
