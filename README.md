<h1 align="center">🤟 Sign Language Recognition (SLR)</h1>

<p align="center">
    <a>LSTM model for ASL recognition built with TensorFlow and Mediapipe</a>‎ ‎ |‎ ‎ <a href="https://slr.jamesjbustos.com/">Demo</a>
    <br>
</p>

https://github.com/jamesjbustos/asl-translator/assets/45052719/b8af48ad-8d45-46ee-ac5d-1bd361f4a2d5

<br>

## About

This project was part of the **INIT Build** program and focused on developing a real-time **Sign Language Recognition (SLR)** model. The goal was to recognize and translate American Sign Language (ASL) signs using a combination of **TensorFlow**, **MediaPipe**, and **OpenCV**. The model was trained on **Google's ASL Kaggle dataset** and designed for real-time applications on both web and edge devices using **TFLite**.

## Model Overview

- **Model Architecture**: Combines **LSTM** and **Transformer** architectures to handle time-series predictions of sign language gestures. The model can also be deployed on edge devices using **TFLite**.
- **Data**: Trained on a dataset of over **100,000 videos**, recognizing **250 ASL signs** with an accuracy of **87%**.

## Technical Details

- **TensorFlow & MediaPipe**: These frameworks were used for hand landmark detection and model training.
- **LSTM & Transformer Architectures**: These models were implemented to capture long-term dependencies in sign language sequences and ensure high accuracy.
- **OpenCV**: Used for video processing and capturing gesture inputs.
- **Streamlit Deployment**: The real-time ASL recognition model was deployed via **Streamlit**, offering a user-friendly interface for live ASL translations on both desktop and mobile.


## Installation

To run locally, follow these steps:

1. Clone the repo:

```bash
git clone https://github.com/jamesjbustos/sign-language-recognition.git
cd asl-translator
```

2. Dependencies:

```bash
pip install requirements.txt
```

3. Streamlit:

```bash
streamlit run app.py
```
