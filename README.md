---

# 🧠 Brain Tumor Classification

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is a brain tumor classification system built using deep learning models (CNN, VGG16, DenseNet121, InceptionV1, and a custom hybrid IDTNet model). It enables the detection and categorization of brain tumors from MRI images with high accuracy.

---

## 📂 Models Included

- ✅ **VGG16** – Modified and fine-tuned for tumor classification  
- ✅ **DenseNet121** – Deep network with dense connectivity  
- ✅ **InceptionV1 (GoogLeNet)** – Efficient multi-scale feature extractor  
- ✅ **IDTNet (Inception-DenseNet hybrid)** – Custom architecture combining inception and dense connections

---

## 🧪 Dataset

- MRI brain images
- 4 classes: `glioma`, `meningioma`, `pituitary`, `no tumor`
- Grayscale images preprocessed and resized to `128x128` or `224x224` depending on model

---

## 🛠️ Technologies Used

- Python
- Keras / TensorFlow
- OpenCV
- NumPy / PIL
- Flask (for web deployment)
- HTML + CSS (for UI)

---

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RayyanKauchali/Brain-Tumor-Classification.git
   cd Brain-Tumor-Classification
````

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app:**

   ```bash
   python app.py
   ```

4. **Access in your browser:**

   ```
   http://localhost:5000
   ```

---

## 📊 Output

* Upload MRI image (`.jpg`, `.png`, `.jpeg`, `.dcm`)
* Prediction: Tumor Type
* Visual confidence output
* Works on desktop and mobile

---

## 📸 UI Preview

![App UI](static/assets/ui_preview.png)
*(Replace this with your actual UI screenshot)*

---

## 📁 Project Structure

```
brain_tumor_ai/
├── app.py                   # Flask application
├── utils.py                 # Image preprocessing and helper functions
├── models/                  # Contains all Keras models (.h5 files)
├── templates/               # HTML templates
├── static/                  # CSS, JS, images
├── requirements.txt         # Dependencies
└── README.md                # Project info
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🌐 Author

**Rayyan Kauchali**
GitHub: [@RayyanKauchali](https://github.com/RayyanKauchali)
Feel free to contribute, suggest improvements, or fork the project!

```
```

