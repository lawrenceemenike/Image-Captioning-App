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
```

### 2. Create and activate a virtual environment

python -m venv venv
source venv/bin/activate  # On macOS/Linux
.\venv\Scripts\activate   # On Windows

### 3. Install the dependencies
pip install -r requirements.txt

### 4. Run the application
python demo.py
Gradio will launch a local web interface. Upload an image and receive a descriptive caption instantly.

## Author’s Note
This is part of my learning journey into multimodal AI applications. If you find this useful or want to build something together, I’d love to hear from you.

## License
This project is open-source under the MIT License.




