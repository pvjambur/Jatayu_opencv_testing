# Jatayu_opencv_testing

---

<img src="https://opencv.org/wp-content/uploads/2020/07/cropped-OpenCV_logo_white_600x.png" width="200"/>

---

# 🧠 Real-Time Face Detection using OpenCV  
Welcome to the **Jatayu OpenCV Testing** project! This repository demonstrates the power of computer vision through real-time face detection using Haar and LBP classifiers.

---

## 🚀 What This Project Covers

In this session/project, we explored:
- Introduction to Face Detection and OpenCV
- Haar and LBP classifier-based detection
- Comparison of detection time and efficiency
- Drawing bounding boxes around detected faces
- Real-time face detection from a webcam feed with live face counting
- Understanding how XML classifiers work behind the scenes
- Concluding with performance-based insights

---

## 📦 Installation Instructions

Before diving into the code, ensure you have the required dependencies installed. Run the following commands:

```bash
pip install opencv-python opencv-python-headless matplotlib numpy
```

Also make sure `git` is installed. If not, install it via:

```bash
pip install gitpython
```

---

## 📁 Cloning the Repository

To get started with this project, clone the repository using the command below:

```bash
git clone https://github.com/pvjambur/Jatayu_opencv_testing.git
```

Now navigate into the project directory:

```bash
cd Jatayu_opencv_testing
```

Follow the instructions provided inside the folder (typically in a `README.md` or notebook/script) to run individual modules.

---

## 🛠 How the XML Classifiers Work

The `.xml` files used in this project contain **pre-trained models** based on Haar or LBP (Local Binary Pattern) features. OpenCV loads these XML files using `cv2.CascadeClassifier`, which then applies the trained pattern recognition algorithm on grayscale images to locate faces or other objects. These classifiers scan the image at multiple scales, searching for feature matches to detect the presence of faces.

---

## ⏱ Real-Time Detection

We also implemented a **30-second timer-based live webcam detector** that:
- Detects and draws bounding boxes on faces
- Displays the number of faces currently in the frame
- Automatically closes after 30 seconds or if 'q' is pressed

---

## 📌 Final Words

This project is a strong starting point for those interested in:
- Computer Vision
- AI-powered surveillance
- Identity recognition & tracking
- Anti-spoofing and biometric verification (upcoming integrations)

We hope you learned a lot from this journey! Happy Coding 💻✨  
Feel free to fork, star ⭐, and contribute to the repository.

---
