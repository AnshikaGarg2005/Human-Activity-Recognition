# Human Activity Recognition (HAR)

## Project Overview
Human Activity Recognition (HAR) using **Deep Learning** is a system designed to identify and classify various human actions from video sequences.

This project implements a **hybrid deep learning architecture** that extracts **spatial features** using Convolutional Neural Networks (CNNs) and captures **temporal dependencies** using Long Short-Term Memory (LSTM) networks. The model learns both appearance and motion patterns to accurately recognize complex human activities.

---

##  Key Features
-  Action recognition from video sequences
-  CNN + LSTM hybrid deep learning model (LRCN)
-  Temporal sequence-based learning
-  Training accuracy and loss visualization
-  Prediction on unseen video data

---

## Dataset
- **Dataset:** UCF50 – Action Recognition Dataset
- **Classes:** 50 human activity categories
- **Examples:** Walking, running, sports, instrument playing, etc.
<img width="954" height="1415" alt="image" src="https://github.com/user-attachments/assets/64383b91-0988-49db-bf08-dc6b661f355a" />


The dataset contains realistic videos recorded under varying conditions, making it suitable for real-world applications.

---

##  Model Architecture
This project follows the **LRCN (Long-term Recurrent Convolutional Network)** approach:

- **TimeDistributed CNN Layers:** Extract spatial features from video frames
- **LSTM Layer:** Learns temporal motion patterns
- **Dense Softmax Layer:** Performs multi-class classification

---

##  Tech Stack
- **Programming Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **Computer Vision:** OpenCV
- **Video Processing:** MoviePy
- **Data Handling:** NumPy, Scikit-learn
- **Visualization:** Matplotlib

---

##  Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/AnshikaGarg2005/Human-Activity-Recognition.git
cd Human-Activity-Recognition
```


### 2️⃣ Dataset Download
https://www.crcv.ucf.edu/data/UCF50.rar


---

## Results
- The model demonstrates stable learning with good convergence
- Performance is evaluated using accuracy and loss metrics
- Training and validation plots are generated within the notebook

---

## Video Input Methods

This project supports multiple ways of providing video input for Human Activity Recognition, making it flexible for demos, testing, and real-world usage.

---

### 1️⃣ YouTube Video URL (Current Implementation)
The system allows users to provide a **YouTube video link** as input.

**How it works:**
- The YouTube video URL is provided by the user
- The video is downloaded using libraries like `pafy` / `youtube-dl`
- Frames are extracted from the video
- The trained CNN–LSTM model predicts the human activity
- 🟢 **No need to upload large video files**


**Advantages:**
- Easy and quick for demonstrations


**Limitations:**
- Requires a stable internet connection
- YouTube links may expire or become unavailable

---

### 2️⃣ Local Video File Upload (.mp4)
The project also supports **local video files** for activity recognition.

**How it works:**
- A `.mp4` video file is uploaded to the project directory (e.g., `media/demo.mp4`)
- Video frames are read using OpenCV or MoviePy
- The model processes the frames and predicts the activity

**Advantages:**
- Works offline
- More stable and reliable

---

### 3️⃣ Google Colab Manual Upload (Optional)
When running the notebook on Google Colab, videos can be uploaded manually.

**How it works:**
- User uploads video using Colab’s upload interface
- File is temporarily stored for inference
- Model processes the video

**Advantages:**
- Simple and quick testing
- No external video hosting required

**Limitation:**
- Uploaded files are lost when the Colab session ends
---



### Summary
The project is designed to be flexible by supporting:
- YouTube video links for easy demos
- Local video files for stable offline inference
- Manual uploads for experimentation


---
### Demo

I successfully played a YouTube video directly by providing the video link in the code. The output is shown below:

<img width="1039" height="529" alt="Demo Output 1" src="https://github.com/user-attachments/assets/348d7486-8fd0-46b5-98ea-8768f51be279" />


<img width="1304" height="723" alt="Demo Output 2" src="https://github.com/user-attachments/assets/d2cb0e1f-fc20-4b7d-9110-483068acb75b" />

**YouTube Video Link:** [https://www.youtube.com/watch?v=6U8ipxSRAUA](https://www.youtube.com/watch?v=6U8ipxSRAUA)
---

## 📁 Project Structure
---
<img width="638" height="237" alt="image" src="https://github.com/user-attachments/assets/10504b6f-334e-4b2e-8d9b-04fb79ad81a1" />

---

##  Future Enhancements
-  Real-time webcam-based action recognition
-  Use of 3D CNNs for better spatio-temporal learning
-  Deployment as a web application
-  Improved accuracy using attention mechanisms

---

## 👩‍💻 Author
**Anshika Garg**  
B.Tech CSE (AIML) | UPES Dehradun  
Deep Learning & Machine Learning Enthusiast
