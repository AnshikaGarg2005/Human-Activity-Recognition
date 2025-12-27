# 🧠 Human Activity Recognition (HAR)

## 📌 Project Overview
Human Activity Recognition (HAR) using **Deep Learning** is a system designed to identify and classify various human actions from video sequences.

This project implements a **hybrid deep learning architecture** that extracts **spatial features** using Convolutional Neural Networks (CNNs) and captures **temporal dependencies** using Long Short-Term Memory (LSTM) networks. The model learns both appearance and motion patterns to accurately recognize complex human activities.

---

## 🎯 Key Features
- 🎥 Action recognition from video sequences
- 🧠 CNN + LSTM hybrid deep learning model (LRCN)
- ⏱️ Temporal sequence-based learning
- 📊 Training accuracy and loss visualization
- 🔍 Prediction on unseen video data

---

## 📊 Dataset
- **Dataset:** UCF50 – Action Recognition Dataset
- **Classes:** 50 human activity categories
- **Examples:** Walking, running, sports, instrument playing, etc.
<img width="954" height="1415" alt="image" src="https://github.com/user-attachments/assets/64383b91-0988-49db-bf08-dc6b661f355a" />


The dataset contains realistic videos recorded under varying conditions, making it suitable for real-world applications.

---

## 🧠 Model Architecture
This project follows the **LRCN (Long-term Recurrent Convolutional Network)** approach:

- **TimeDistributed CNN Layers:** Extract spatial features from video frames
- **LSTM Layer:** Learns temporal motion patterns
- **Dense Softmax Layer:** Performs multi-class classification

---

## ⚙️ Tech Stack
- **Programming Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Computer Vision:** OpenCV
- **Video Processing:** MoviePy
- **Data Handling:** NumPy, Scikit-learn
- **Visualization:** Matplotlib

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/AnshikaGarg2005/Human-Activity-Recognition.git
cd Human-Activity-Recognition


### 2️⃣ Dataset Download
The notebook includes automated scripts to download and extract the dataset:
wget --no-check-certificate https://www.crcv.ucf.edu/data/UCF50.rar
unrar x UCF50.rar


---

## 📈 Results
- The model demonstrates stable learning with good convergence
- Performance is evaluated using accuracy and loss metrics
- Training and validation plots are generated within the notebook

---

## 🎥 Demo Video

### ▶️ GitHub Video (Recommended)
Upload your `.mp4` file to the repository  
(root directory or `media/` folder)  
GitHub will auto-generate a playable link

https://github.com/AnshikaGarg2005/Human-Activity-Recognition/assets/VIDEO_ID


### ▶️ YouTube Demo (Optional)
[![Demo Video](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/0.jpg)]
(https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID)

---
## 📁 Project Structure
---
<img width="638" height="237" alt="image" src="https://github.com/user-attachments/assets/10504b6f-334e-4b2e-8d9b-04fb79ad81a1" />

---

## 🌱 Future Enhancements
- 🎥 Real-time webcam-based action recognition
- 🧠 Use of 3D CNNs for better spatio-temporal learning
- 🌐 Deployment as a web application
- 🔍 Improved accuracy using attention mechanisms

---

## 👩‍💻 Author
**Anshika Garg**  
B.Tech CSE (AIML) | UPES Dehradun  
Deep Learning & Computer Vision Enthusiast
