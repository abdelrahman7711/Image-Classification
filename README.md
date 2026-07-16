# 🌍 Intel Image Classification using Deep Learning

A deep learning project for **multi-class scene classification** using the **Intel Image Classification Dataset**. This project compares the performance of a **Custom CNN** and **Transfer Learning with MobileNetV2** for recognizing different natural scenes.

---

## 📌 Project Overview

Image classification is one of the most important applications of Pattern Recognition and Computer Vision. In this project, deep learning models are trained to classify natural scene images into six different categories using the Intel Image Classification dataset.

The project demonstrates the complete machine learning pipeline, including:

- Dataset preprocessing
- Data augmentation
- Feature extraction
- Model training
- Performance evaluation
- Comparison between a custom CNN and a pretrained MobileNetV2 model

---

## 🎯 Dataset

**Intel Image Classification Dataset**

The dataset contains approximately **25,000 images** belonging to six scene categories:

- 🏢 Buildings
- 🌲 Forest
- ⛰️ Glacier
- 🏔️ Mountain
- 🌊 Sea
- 🛣️ Street

Images are automatically downloaded using **KaggleHub**.

---

## ✨ Features

- Multi-class image classification
- Automatic dataset download using KaggleHub
- Data preprocessing and augmentation
- Custom CNN implementation
- Transfer Learning using MobileNetV2
- Model evaluation and comparison
- Confusion Matrix
- Classification Report
- Accuracy & Loss visualization

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- KaggleHub

---

## 🧠 Models

### 1. Custom CNN

The custom model includes:

- Convolution Layers
- MaxPooling Layers
- Dropout
- Flatten Layer
- Dense Layers
- Softmax Output

---

### 2. MobileNetV2 (Transfer Learning)

The pretrained MobileNetV2 model is used as a feature extractor with:

- ImageNet pretrained weights
- Global Average Pooling
- Dropout
- Dense Classification Layer
- Softmax Activation

Transfer learning significantly improves classification performance while reducing training time.

---

## 📊 Data Preprocessing

The preprocessing pipeline includes:

- Automatic dataset download
- Image resizing (224 × 224)
- Normalization
- Data augmentation
  - Rotation
  - Zoom
  - Horizontal Flip
- Training / Validation split
- Test dataset preparation

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/intel-image-classification.git

cd intel-image-classification
```

Install dependencies

```bash
pip install tensorflow
pip install kagglehub
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install numpy
```

or simply

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Patternprojectafteredit.ipynb
```

Run all notebook cells sequentially.

---

## 📈 Model Evaluation

The notebook evaluates the trained models using:

- Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

---

## 📁 Project Structure

```
Intel-Image-Classification/
│
├── Patternprojectafteredit.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## 📊 Classes

| Label | Class |
|--------|-------|
| 0 | Buildings |
| 1 | Forest |
| 2 | Glacier |
| 3 | Mountain |
| 4 | Sea |
| 5 | Street |

---

## 📷 Results

The notebook provides visualizations including:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- Sample Predictions

You can add screenshots inside an `images/` folder:

```
images/
├── dataset_samples.png
├── training_accuracy.png
├── training_loss.png
├── confusion_matrix.png
└── predictions.png
```

---

## 🔬 Pattern Recognition Pipeline

This project follows the standard Pattern Recognition workflow:

1. Data Collection
2. Image Preprocessing
3. Data Augmentation
4. Feature Extraction
5. Model Training
6. Classification
7. Performance Evaluation

---

## 🚀 Future Improvements

- EfficientNet
- ResNet50
- DenseNet121
- Vision Transformers (ViT)
- Hyperparameter tuning
- Explainable AI (Grad-CAM)
- Model deployment using Streamlit
- Real-time image prediction

---

## 👨‍💻 Author

**Your Name**

B.Sc. in Computer Science (Artificial Intelligence)

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

## 📄 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this project for educational and research purposes.

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
