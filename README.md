


---

# Sign Language Recognition System using AI & OpenCV


> **Real-time American Sign Language (ASL) recognition using Computer Vision, Mediapipe, and Deep Learning — with voice output.**

---

## **Project Overview**

This intelligent system recognizes **hand gestures** from a live webcam feed and converts them into **spoken language** using AI.  
It leverages **PyTorch for classification**, **Mediapipe for hand tracking**, and **pyttsx3** for text-to-speech output.  
Designed to assist in communication for the deaf and mute communities, this project promotes inclusion and accessibility.

---

## **Key Features**

- **Live Hand Sign Detection** via webcam
- **Gesture Classification** using a trained CNN model
- **3D Hand Tracking** with Google’s Mediapipe
- **Speech Output** via pyttsx3 when pressing `S`
- **Manual ROI Selection** using CSRT Tracker with key `T`
- **Fully Multithreaded** for seamless voice feedback
- **Intuitive GUI** using OpenCV with live annotations

---

## **Dataset Used**

- **Sign Language MNIST**  
  [Kaggle Dataset Link](https://www.kaggle.com/datamunge/sign-language-mnist)  
  Consists of labeled grayscale images (28x28) for alphabet signs (A–Z), excluding J and Z due to dynamic motion requirements.

![ASL Dataset](https://github.com/mariomaibrahim)

---

## **Project Goals**

1. Empower deaf individuals to communicate freely in classrooms.
2. Promote inclusion of hearing-impaired students in mainstream education.
3. Help non-signers (e.g., tourist guides) interact using sign language.

---

## **System Requirements**

> **Note:** Mediapipe works best with **Python 3.8.10**

### Required Libraries:

Install all dependencies with:

```bash
pip install opencv-python
pip install numpy
pip install autocomplete
pip install mediapipe
pip install torch torchvision
pip install pyttsx3

Or use this snippet in a requirements.txt:

opencv-python
numpy
autocomplete
mediapipe
torch
pyttsx3

```
---

How to Run
---
1. Clone the repository:

git clone 
https://github.com/mariomaibrahim
cd AiTP_project_SIGN_LANGUAGE_DETECTOR_1



2. Ensure your Python version is 3.8.10 (for Mediapipe compatibility)


3. Launch the application:

python main.py



Controls


---

Architecture Overview
---
Camera Input →

Hand ROI Extraction (auto/manual) →

Image Preprocessing (28x28 grayscale) →

CNN Model Prediction (PyTorch) →

Sign Mapping →

Audio Output (TTS)


---
Team Members
---
Marwan Mohamed

Youssef Ahmed

Mariam Ibrahim

Mariam Eid

Mariam Rizk



---

Supervisors
---
Dr. Osama El Nahas

Dr. Hesham Ali

Dr. Nehal El Azali

