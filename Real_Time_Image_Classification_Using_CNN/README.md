# 🖼️ Real-Time Image Classification with MobileNetV2

This project demonstrates **real-time image classification** using a pre-trained **MobileNetV2** model on the ImageNet dataset.  
It captures frames from your webcam, processes them, and overlays the top prediction directly on the video stream.

---

## 🚀 Features
- Loads **MobileNetV2** pre-trained on ImageNet.
- Captures live video from your webcam.
- Preprocesses frames (resize, RGB conversion, normalization).
- Predicts the top class in real time.
- Displays prediction label and confidence score on the video feed.
- Press **`q`** to quit the application.

---

## 📂 Project Structure

```
ImageClassifier/
├── ImageClassifier.py   # Main script with real-time classification
├── requirements.txt     # Dependencies
├── .gitignore           # Ignore unnecessary files
├── LICENSE              # MIT License
└── README.md            # Documentation

```

---

## ⚙️ Requirements
Install the following dependencies before running the project:

bash
pip install -r requirements.txt

▶️ Usage
Run the script directly:

python ImageClassifier.py

Ensure your webcam is connected and accessible.

A window will open showing the live feed with predictions.

Press q to exit.


🧠 Model Details
Architecture: MobileNetV2

Dataset: ImageNet (1,000 classes)

Input size: 224 × 224 × 3 (RGB)

Preprocessing: preprocess_input from Keras Applications

🔧 Possible Improvements
Show Top-3 predictions instead of just one.

Optimize performance by predicting every n frames.

Add command-line arguments for camera ID and number of predictions.

Extend to object detection (YOLO, SSD, Faster R-CNN).

Fine-tune MobileNetV2 on a custom dataset for domain-specific tasks.


🏆 Author : Abhijeet Suresh Gorale

Aspiring Data Scientist

Exploring deep learning, Python, and Golang

GitHub: https://github.com/AbhijeetGorale

Linkdin: www.linkedin.com/in/abhijeetgorale

