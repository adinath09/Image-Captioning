
# 🖼️ Image Captioning Web App using BLIP

This is a simple image captioning web application that uses the **pretrained BLIP (Bootstrapping Language-Image Pre-training)** model to generate captions for uploaded images. The backend is built with Flask, and the interface is rendered using a static HTML template.

## 🔍 About the Project

- 🚀 Uses **BLIP (Salesforce/blip-image-captioning-base)** via HuggingFace Transformers
- 🖼️ Upload an image and get a descriptive caption
- 🌐 Simple Flask backend with static HTML/CSS frontend
- ⚡ No training required – uses pretrained models


## 🧰 Tech Stack

- **Python 3.9+**
- **Flask** – Web server
- **HuggingFace Transformers** – For BLIP model
- **Pillow / OpenCV** – For image processing (optional)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/image-captioning.git
cd image-captioning
````

### 2. (Optional) Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python app.py
```

Then open your browser and go to `http://localhost:5000`.

## 📷 Example

1. Upload Image
2. Get Caption
   *"A dog is running through a grassy field with a ball in its mouth."*

## 📦 Requirements

Example `requirements.txt`:

```txt
flask
torch
transformers
Pillow
```

## 🤖 Model Used

* [Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)

This model is loaded using the HuggingFace `transformers` library and performs image captioning with zero-shot inference.

## ✍️ Author

Made with ❤️ by Adinath Nage
[GitHub](https://github.com/adinat09) • [LinkedIn](https://linkedin.com/in/adinathnage)

