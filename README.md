# 🩺 Non-Invasive Blood Glucose Measurement System

## 📌 Overview
This project aims to develop a **non-invasive blood glucose measurement system** using biomedical sensing and embedded systems techniques.  
The goal is to explore alternative methods to traditional invasive glucose monitoring by leveraging **optical sensing and machine learning**.

---

## 🎯 Project Objectives
- Design a non-invasive glucose measurement prototype
- Explore optical-based sensing techniques
- Evaluate the feasibility of image-based machine learning for glucose classification
- Gain hands-on experience in biomedical device development

---

## 🛠️ Methods & Approaches

### 🔹 Method 1: Hardware-Based Measurement
- **ESP32 microcontroller**
- **Laser diode**
- **Photodiodes**
- Optical signal acquisition and processing

This method focused on collecting optical signals from biological tissue using laser illumination and photodiodes.

---

### 🔹 Method 2: Image-Based Machine Learning
- Phone camera + laser diode
- Dataset of **48 laser-based images**
- Image classification model

This method explored the possibility of estimating glucose levels using image processing and machine learning techniques.

---

## 🧰 Tools & Technologies
- ESP32
- Python
- OpenCV
- Machine Learning
- Laser Diode
- Photodiodes
- Embedded Systems
- Biomedical Signal Processing

---

## 📊 Results
- The **hardware-based approach** showed promising experimental behavior.
- The **image-based ML model** did not achieve high accuracy due to:
  - Very small dataset size
  - High noise and low feature variation in images

---

## ⚠️ Challenges
- Limited dataset (only 48 images)
- Sensitivity to lighting and noise in laser images
- Difficulty in extracting discriminative features for ML models

---

## 📚 Learning Outcomes
- Practical experience in **medical device prototyping**
- Understanding the limitations of machine learning with small datasets
- Hands-on work with **ESP32 and optical sensors**
- Exposure to computer vision challenges in biomedical applications

---

## 🚀 Future Improvements
- Increase dataset size significantly
- Apply data augmentation techniques
- Use regression models instead of classification
- Improve optical setup stability
- Explore signal-based analysis instead of image-based methods

---

## 👤 Author
**Islam Ayman**  
Biomedical Engineering Student  
Interested in Medical Devices, AI in Healthcare, and Embedded Systems

---

## 📎 Notes
This project was conducted as an academic and experimental study.  
The image-based approach is presented as a **learning experience** rather than a finalized medical solution.
