# 🎭 Deep Fake Face Detection Using Machine Learning

## 📌 Project Overview

This project is a **Deepfake Face Detection System** that identifies whether a video or image is real or manipulated using machine learning and deep learning techniques. It analyzes facial patterns, inconsistencies, and artifacts to detect synthetic media.

---

## 🚀 Features
- Detects deepfake faces in images and videos  
- Uses machine learning and deep learning models  
- Web-based interface using Flask  
- Automated facial analysis and classification  
- Supports real-time detection (based on system performance)  

---

## 🖥️ Hardware Requirements
- Minimum **8GB RAM** (16GB recommended)  
- Processor with **AVX support**  
- **GPU (Optional)** for faster execution  

---

## 💻 Software Requirements
- Operating System: Windows / macOS / Linux  
- Anaconda  
- Python **3.9.2**  

---

## ⚙️ Environment Setup

1. Open **Anaconda Navigator**  
2. Go to **Environments**  
3. Click on **Create**  
4. Name the environment: `home-project`  
5. Select Python version: **3.9.2**  
6. Click **Create**  

---

## 📦 Installation

Open terminal or command prompt and run the following:

```bash
conda activate home-project

conda install -c conda-forge notebook
pip install tensorflow
conda install -c conda-forge keras
conda install -c anaconda scikit-learn
conda install -c conda-forge opencv
conda install -c anaconda scikit-image
conda install -c anaconda flask
pip install pandas
pip install werkzeug==2.3.7
pip install cmake
conda install -c conda-forge dlib
pip install torch==2.0.1
pip install torchvision==0.15.2
pip install numpy==1.24.2
pip install matplotlib==3.6.2
pip install face-recognition

```

▶️ Running the Project

1. Navigate to the project directory:

```bash

cd path\to\your\folder

```
2. Run the application:

```bash

python app.py

```
3. Open your browser and go to:

```bash

http://127.0.0.1:5000

```


📊 Technologies Used

    Python
    TensorFlow
    Keras
    OpenCV
    Scikit-learn
    Flask
    PyTorch
    Dlib
    NumPy
    Matplotlib
    
📷 Working Principle

1. Extracts frames from video or processes images
2. Detects faces using computer vision techniques
3. Analyzes facial features and inconsistencies
4. Classifies content as Real or Deepfake

🔮 Future Enhancements

1. Improve detection accuracy using advanced models
2. Add real-time webcam detection
3. Deploy as a web/cloud application
4. Improve user interface and experience


👩‍💻 Author

Yogeshwari S Gowda
