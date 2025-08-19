


# Bank Security Alert System Using Face Recognition

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-orange?logo=tensorflow)
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey)
[![DOI](https://img.shields.io/badge/DOI-10.15680%2FIJIRCCE.2023.1103071-blue)](https://doi.org/10.15680/IJIRCCE.2023.1103071)

---

## 📌 Overview

This project presents an **AI-powered security system** that leverages **deep learning and computer vision** to enhance bank security. By integrating **Convolutional Neural Networks (CNNs)** with **face recognition technology**, the system detects unauthorized individuals and immediately triggers alerts to prevent unauthorized access.

The solution provides a **reliable, efficient, and real-time monitoring system** for banking premises, ensuring improved safety of customers, employees, and assets.

---

## 🔍 Features

* **Face Recognition Authentication** – Detects and verifies individuals using CNN-based models.
* **Real-Time Alerts** – Sends instant notifications to security staff via mobile/email when unknown individuals are detected.
* **Automated Security Layer** – Eliminates dependency on manual monitoring and reduces human error.
* **High Accuracy & Efficiency** – Uses deep learning to improve recognition performance and reduce false alarms.
* **Cost-Effective & Scalable** – Designed to be inexpensive and adaptable to modern banking infrastructures.

---

## 🛠️ Methodology

The project employs a **Convolutional Neural Network (CNN)** architecture with the following pipeline:

```mermaid
flowchart TD
    A[Input Image (Webcam)] --> B[Convolution Layer]
    B --> C[ReLU Activation]
    C --> D[Pooling Layer (Max Pooling)]
    D --> E[Flattening Layer]
    E --> F[Fully Connected Layer]
    F --> G{Authorized?}
    G -- Yes --> H[Access Granted]
    G -- No --> I[Alert System (SMS/Email)]
```

Additional components include:

* **Webcam Integration** for live face capture.
* **Authentication Module** for authorized user training.
* **Alert System** that sends SMS/email notifications when intrusions are detected.

---

## 📊 Results

* Successfully detects **unknown individuals** in real time.
* Provides **alerts via mobile and email** to enhance response times.
* Demonstrated efficiency, low complexity, and reduced operational costs compared to traditional security systems.

---

## 📸 Screens & Interfaces

* **Home Page** – Entry point for users.
* **Data Collection Page** – Used for training and storing authorized user data.
* **Training Authentication Page** – Allows administrators to authenticate and manage training data.
* **Face Recognition Page** – Real-time detection and recognition interface.

---

## 📚 References

The research is published in:
**International Journal of Innovative Research in Computer and Communication Engineering (IJIRCCE), Volume 11, Issue 3, March 2023**
DOI: [10.15680/IJIRCCE.2023.1103071](https://doi.org/10.15680/IJIRCCE.2023.1103071)&#x20; 

---

## 👩‍💻 Authors

* B Antony Lokesh


Department of Information Technology, Kallam Haranadhareddy Institute of Technology, Chowdavaram, Guntur, Andhra Pradesh, India.

---

## ⚠️ Disclaimer

This project was developed as part of my **Undergraduate (UG) studies**, and the associated research paper was **published in the International Journal of Innovative Research in Computer and Communication Engineering (IJIRCCE), Volume 11, Issue 3, March 2023** (DOI: 10.15680/IJIRCCE.2023.1103071) ([mite.ac.in][1], [ijircce.com][2]).

You can view the full paper here: [Research Paper (PDF) on GitHub](https://github.com/Antonylokesh/Bank-Security-Alert-System-Using-Face-Recognition-Research-Paper-/blob/main/Research%20paper.pdf) ([github.com][3]).

The code and documentation in this repository are intended **solely for academic and educational purposes** and should **not be considered a production-ready security system**.






