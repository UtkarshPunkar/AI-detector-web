# 🤖 AI vs Real Image Detector

A deep learning based web application that detects whether an image is **AI-generated** or **Real** using **MobileNetV2 (Transfer Learning)** and runs entirely in the browser via **TensorFlow.js**.

---

## 🚀 Live Demo:

🔗 https://utkarshpunkar.github.io/AI-detector-web/

---

## 📌 Features:

* 🖼 Upload and analyze any image
* ⚡ Real-time prediction (browser-based)
* 🧠 Transfer Learning with MobileNetV2
* 🌐 No backend required

---

## 🧠 Model Details:

* Model: MobileNetV2 (Pretrained on ImageNet)
* Input Size: 224 × 224
* Output: Binary (AI vs Real)
* Framework: TensorFlow / Keras
* Deployment: TensorFlow.js

---

## 📂 Full Project Structure (Development):

```id="lxt9qg"
ai-image-detector/
│
├── dataset/
│   ├── train/
│   │   ├── ai/
│   │   └── real/
│   └── val/
│       ├── ai/
│       └── real/
│
├── model/
│   └── ai_detector.h5
│
├── web/
│   ├── index.html
│   └── model/
│       ├── model.json
│       ├── group1-shard*.bin
│
├── train.py
├── requirements.txt
└── README.md
```

---

## 🌐 Deployment Structure (GitHub Pages):

```id="ss4d1g"
ai-detector-web/
│
├── index.html
├── model/
│   ├── model.json
│   ├── group1-shard*.bin
```

---

## ⚙️ How It Works:

1. User uploads image
2. Image resized to 224×224
3. Pixel normalization (0–1)
4. Model predicts probability
5. Output displayed as:

   * 🧠 AI Generated
   * 📷 Real Image

---

## 🛠 Tech Stack:

* Python (Model Training)
* TensorFlow / Keras
* TensorFlow.js
* HTML, CSS, JavaScript

---

## 📊 Training Details:

* Dataset: AI vs Real images
* Preprocessing: Rescaling (1/255)
* Loss: Binary Crossentropy
* Optimizer: Adam
* Transfer Learning: Frozen base layers

---

## 👨‍💻 Author

**Utkarsh Punkar**

