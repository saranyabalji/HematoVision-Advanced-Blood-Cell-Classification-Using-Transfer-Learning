# 🧬 HematoVision: Advanced Blood Cell Classification Using Transfer Learning

HematoVision is a deep learning web application that classifies microscopic blood cell images into four types:
- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

It uses **Transfer Learning (MobileNetV2)** for high accuracy and is built with **Flask** for a simple, interactive web interface.

---

## 🚀 Demo

📷 Upload a blood cell image → 🧠 Model predicts the cell type → 📊 Result with image preview

---

## 🛠️ Tech Stack

- **Model:** TensorFlow / Keras (MobileNetV2)
- **Web Framework:** Flask
- **Preprocessing:** OpenCV
- **Frontend:** HTML + CSS (with base64 image rendering)

---

## 📦 Project Structure

```bash
HematoVision/
├── app.py # Flask app
├── Blood Cell.h5 # Pretrained model file (~60MB)
├── requirements.txt # Python dependencies
├── static/ # Uploaded images go here
└── templates/ # HTML pages
    ├── home.html # Upload page
    └── result.html # Result display page
```

---

## 💻 Run Locally

Open Command prompt (Anaconda prompt if exists) in your system and follow the below commands
### 1. Clone the Repository

```bash
git clone https://github.com/Mineesh-B/HematoVision-Advanced-Blood-Cell-Classification-Using-Transfer-Learning.git
cd HematoVision-Advanced-Blood-Cell-Classification-Using-Transfer-Learning
```
### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
venv\Scripts\activate       # Windows
# source venv/bin/activate   # macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Flask App

```bash
python app.py
```

Then go to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.












