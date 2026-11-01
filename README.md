# Emotion_Detection_Live


# 🎭 Emotion Detection Using Deep Learning

### 🧠 Real-Time Facial Emotion Recognition with MobileNetV2 & OpenCV

**An AI-powered Computer Vision project that detects faces and classifies facial expressions using Deep Learning.** 🚀

---

## 🎯 About the Project

Emotion Detection is a Deep Learning and Computer Vision project designed to classify facial expressions from images and webcam video.

The project uses **MobileNetV2 Transfer Learning** to extract facial features and a custom classification head to predict emotion categories. OpenCV is used for face detection and real-time webcam processing.

The primary objective is to build a practical AI application that combines image classification, Transfer Learning, and Computer Vision.

## ✨ Key Features

- 🎭 Facial emotion classification using Deep Learning.
- 🧠 Transfer Learning with pretrained MobileNetV2.
- 👁️ Face detection using OpenCV Haar Cascades.
- 📹 Real-time webcam-based emotion prediction.
- 🔄 Image augmentation for improved model generalization.
- ⚡ Two-phase training with feature extraction and fine-tuning.
- 📊 Training and validation accuracy visualization.
- 💾 Saving the trained model for future predictions.

## 🛠️ Technologies Used

| Technology | Application |
|---|---|
| 🐍 Python | Core programming |
| 🧠 TensorFlow & Keras | Deep Learning and model training |
| 📱 MobileNetV2 | Transfer Learning and feature extraction |
| 👁️ OpenCV | Face detection and webcam processing |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Training visualization |
| 📓 Jupyter Notebook | Model development and experimentation |

## ⚙️ How It Works

📸 **Input Image / Webcam**  
⬇️  
👤 **Face Detection using OpenCV**  
⬇️  
🖼️ **Image Preprocessing and Resizing**  
⬇️  
🧠 **Feature Extraction using MobileNetV2**  
⬇️  
🎯 **Emotion Classification using Softmax**  
⬇️  
📊 **Predicted Emotion Output**

## 🧠 Model Architecture

The model uses a pretrained MobileNetV2 backbone with a custom classification head.

- **Input Shape:** `96 × 96 × 3`
- **Preprocessing:** Pixel rescaling to `[-1, 1]`
- **Feature Extractor:** MobileNetV2 pretrained on ImageNet
- **Pooling:** Global Average Pooling
- **Regularization:** Dropout with a rate of `0.3`
- **Output Layer:** Dense layer with Softmax activation
- **Optimizer:** Adam
- **Training Strategy:** Feature extraction followed by fine-tuning

This approach reuses pretrained visual features and adapts selected layers to the target emotion dataset.

## 📈 Model Evaluation

The notebook evaluates the trained model on the supplied test dataset and visualizes training progress.

Evaluation focuses on:

- 📊 Training Accuracy
- 📉 Training Loss
- 🎯 Validation Accuracy
- 📈 Validation Loss
- 🧪 Test Dataset Performance

*Actual performance metrics should be added after running the model. The notebook uses the test dataset for validation during training, so an independent test set is recommended for a reliable final evaluation.*

## 👨‍💻 Connect With Me

**Dheeraj Chouhan**  
💡 Aspiring AI/ML Engineer

- 🐙 **GitHub:** [dheeraj24-coder](https://github.com/dheeraj24-coder)
- 💼 **LinkedIn:** https://www.linkedin.com/in/dheeraj-chouhan-7a6996371/
- 📧 **Email:** dheerajchouhan4466@gmail.com

---


### 🚀 Building Intelligent Solutions with AI

**Made with ❤️ using Python, Deep Learning & Computer Vision**
