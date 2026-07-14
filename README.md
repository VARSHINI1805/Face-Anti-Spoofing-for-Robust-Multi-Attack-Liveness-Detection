# Face Anti-Spoofing for Robust Multi-Attack Liveness Detection

## 📌 Project Overview

Face recognition has become one of the most widely used biometric authentication methods in smartphones, banking systems, online examinations, healthcare, and access control. However, these systems are vulnerable to spoofing attacks such as printed photographs, replay videos, mobile screen displays, and 3D masks, allowing unauthorized users to gain access.

This project proposes a deep learning-based Face Anti-Spoofing system capable of detecting multiple spoof attack types while accurately distinguishing between live and fake faces. The system aims to improve biometric authentication security by preventing spoofing attacks before authentication.

---

# 🎯 Problem Statement

Traditional face recognition systems can be easily deceived by spoofing attacks using printed photos, replay videos, mobile screens, and masks. Existing systems often fail to distinguish between a genuine user and a spoof attack, creating significant security risks.

The proposed system uses deep learning techniques to detect live faces and identify different spoof attack types in real time before granting access.

---

# 🎯 Objectives

- Develop a robust face anti-spoofing system.
- Detect live and spoof faces accurately.
- Identify multiple spoof attack types.
- Improve the security of biometric authentication systems.
- Provide real-time authentication support.

---

# 🚀 Proposed Solution

The system captures a user's face using a webcam or mobile camera. After detecting and preprocessing the face image, a deep learning model extracts facial features and classifies the input as either a live face or one of several spoof attack types.

Only genuine users are granted access, while spoof attempts are denied.

---

# ⚙️ System Workflow

1. Capture Face
2. Face Detection
3. Face Preprocessing
4. Feature Extraction
5. Multi-Attack Classification
6. Authentication Decision

---

# 🔥 Key Features

- Real-Time Face Detection
- Live Face Verification
- Printed Photo Attack Detection
- Mobile Screen Replay Detection
- Video Replay Attack Detection
- 3D Mask Detection
- High Accuracy Classification
- Secure Authentication

---

# 💡 Project Novelty

Unlike traditional systems that only classify faces as **Real** or **Fake**, this project identifies multiple spoof attack types individually. This provides better security by recognizing the specific type of spoof attack and improving authentication reliability.

Future enhancements may include explainable AI techniques to visualize the facial regions influencing the model's predictions.

---

# 🧠 Technology Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Deep Learning
- OpenCV
- MediaPipe
- PyTorch
- NumPy
- Pandas

---

# 📂 Dataset

The project utilizes publicly available face anti-spoofing datasets:

- CASIA Face Anti-Spoofing (CASIA-FASD)
- Replay-Attack
- OULU-NPU
- CelebA-Spoof

---

# 📊 Expected Output

The system predicts one of the following:

- ✅ Live Face
- ❌ Printed Photo Attack
- ❌ Mobile Screen Replay Attack
- ❌ Video Replay Attack
- ❌ 3D Mask Attack

Authentication is granted only when a live face is detected.

---

# 🌍 Applications

- Smartphone Authentication
- Banking and Financial Services
- Online Examination Systems
- Smart Attendance Systems
- Airport and Border Security
- Enterprise Access Control
- Digital Identity Verification
- E-Government Services





