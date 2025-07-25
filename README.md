
---

```markdown
# 🧠 Brain Tumor Classification using Deep Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project aims to classify brain tumors from MRI images using deep learning models including **VGG16**, **DenseNet121**, **InceptionV1**, and a custom hybrid model called **IDTNet** (Inception + DenseNet). The goal is to assist radiologists in early and accurate tumor diagnosis using computer-aided detection.

---

## 📌 Objective

To design a robust deep learning-based classification system capable of identifying and categorizing brain tumors from MRI images into one of four classes:
- **Glioma**
- **Meningioma**
- **Pituitary**
- **No Tumor**

---

## 🧪 Models Implemented

| Model        | Highlights |
|--------------|------------|
| **VGG16**    | 16-layer architecture with pre-trained ImageNet weights, fine-tuned for medical imaging |
| **DenseNet121** | Dense connectivity and efficient parameter usage |
| **InceptionV1 (GoogLeNet)** | Multi-scale convolution layers for feature extraction |
| **IDTNet**   | Custom hybrid combining Inception and DenseNet blocks for enhanced performance |

---

## 📂 Dataset Details

- **Type**: Brain MRI scans  
- **Classes**: Glioma, Meningioma, Pituitary, No Tumor  
- **Input Size**: `128x128` or `224x224` RGB images  
- **Format**: JPEG / PNG

> The dataset used in this project contains preprocessed grayscale images with balanced class distribution.

---

## ⚙️ Project Structure

```

brain\_tumor\_ai/
├── models/                  # Trained model files (.keras)
├── static/uploads/          # Uploaded images via web app
├── templates/               # HTML templates for Flask
├── app.py                   # Flask backend
├── utils.py                 # Image preprocessing, model loading, prediction
├── requirements.txt         # Python dependencies
└── README.md                # Project overview

````

---

## 🌐 Web Application Features

- Upload MRI image (JPG/PNG)
- Choose classification model (VGG16, DenseNet121, InceptionV1, IDTNet)
- Get predicted tumor class and confidence score
- Responsive design (works on mobile and desktop)

---

## 💻 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/RayyanKauchali/Brain-Tumor-Classification.git
cd Brain-Tumor-Classification
````

### 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
# Activate:
venv\Scripts\activate       # on Windows
source venv/bin/activate    # on macOS/Linux
```

### 3. Install required packages

```bash
pip install -r requirements.txt
```

### 4. Run the Flask app

```bash
python app.py
```

Access it at:
➡️ `http://127.0.0.1:5000`

---

## 🧠 Sample Output

* Input: Brain MRI Image
* Output: Tumor Class → e.g., `Pituitary Tumor`
* Confidence: e.g., `98.6%`

---

## 📊 Performance Metrics

| Model      | Accuracy | Precision | Recall  | F1-Score |
| ---------- | -------- | --------- | ------- | -------- |
| VGG16      | \~96%    | High      | High    | High     |
| DenseNet   | \~98%    | High      | High    | High     |
| Inception  | \~97%    | High      | High    | High     |
| **IDTNet** | **99%**  | Highest   | Highest | Highest  |

> IDTNet showed best overall performance on test data.

---

## 🔐 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Rayyan Kauchali**
📧 [LinkedIn](https://www.linkedin.com/in/rayyankauchali)
💻 [GitHub](https://github.com/RayyanKauchali)

---

## 🙌 Acknowledgments

* Dataset sourced from publicly available brain MRI data
* Inspired by various medical deep learning studies and architectures

```

---

Let me know if you'd like a similarly styled `index.md` for GitHub Pages or a `LICENSE` file too!
```
