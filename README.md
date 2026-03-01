# Realtime Sign Language Detection Using LSTM Model

![Screenshot 2025-11-19 at 2 15 50 PM](https://github.com/user-attachments/assets/6ae850a8-6cbb-46f6-8d25-0ecb3b57fe1e)


> The Realtime Sign Language Detection Using LSTM Model is a deep learning-based project that aims to recognize and interpret sign language gestures in real-time. It utilizes a Long Short-Term Memory (LSTM) neural network architecture to learn and classify sign language gestures captured from a video feed. The project provides a user-friendly interface where users can perform sign language gestures in front of a camera, and the system will instantly detect and interpret the gestures. This can be used as an assistive technology for individuals with hearing impairments to communicate effectively. Key features of the project include real-time gesture detection, high accuracy in recognition, and the ability to add and train new sign language gestures. The system is built using Python, TensorFlow, OpenCV, and Numpy, making it accessible and easy to customize. With the Realtime Sign Language Detection Using LSTM Model, we aim to bridge the communication gap and empower individuals with hearing impairments


## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How to Add New Gestures?](#how-to-add-new-gestures?)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

This project implements a Realtime Sign Language Detection System using LSTM-based deep learning and Mediapipe pose/hand landmark detection.
The system captures hand & body keypoints from a live webcam feed, processes them into sequences, and passes them to an LSTM neural network that recognizes gestures in real-time.

This project is ideal for:

	•	Assistive communication tools
	•	Human-computer interaction
	•	Gesture-based interfaces
	•	ML/DL academic projects
	•	Real-time inference applications

The system is built using:

``
✔ Python 3.8
✔ Mediapipe
✔ OpenCV
✔ TensorFlow / Keras LSTM
✔ NumPy
``

## Features

	•	Realtime gesture prediction (30 FPS)
	•	High-accuracy LSTM-based recognition
	•	Modular architecture — easy to add new gestures
	•	Uses Mediapipe Holistic for human keypoints
	•	Works with any webcam
	•	Clean, reusable training & inference pipelines
	•	Trained LSTM model for multiple gesture classes


##  Demo Video

[![Watch the Demo](https://img.youtube.com/vi/FGgRwOvy6ws/0.jpg)](https://youtu.be/FGgRwOvy6ws?si=uqnT5M5oIDgXpcrv)

## Getting Started

To get started with the Realtime Sign Language Detection Using LSTM Model, follow these steps:

### Prerequisites

Install the following:
	
	•	Python 3.8+
	•	Mediapipe
	•	OpenCV
	•	TensorFlow
	•	NumPy

## Installation

### 1️⃣ Clone the Repository
```shell
git clone https://github.com/akashcodes23/Realtime-Sign-LanguageDetection.git
cd Realtime-Sign-LanguageDetection
```

### 2️⃣ Install Dependencies

```shell
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook 

```shell
jupyter notebook
```

Open:

RealTimeSignLanguageDetection.ipynb


## Usage (Run the full System)

Run Realtime Prediction

```shell
python main.py
```


## Project Structure


```shell
Realtime-Sign-LanguageDetection
│── main.py                     # Realtime prediction script
│── Train.ipynb                 # Training pipeline (LSTM)
│── RealTimeSignLanguageDetection.ipynb
│── v2/                         # Dataset & preprocessing
│── model.h5 / model_weights.h5 (optional)
│── requirements.txt
│── README.md
```

## How to Add New Gestures?

1. Go to notebook **Train.ipynb**
2. Add the new gesture class
3. Record new gesture samples using Mediapipe
4. Retrain the LSTM
5. Save the new model
6. Run main.py again

The system is modular, so adding new classes is very easy.


## Contributing

We welcome contributions from developers, researchers, and enthusiasts.

You can contribute by:
- Introducing new gesture classes to the LSTM model
- Optimizing model training, preprocessing, or real-time inference
- Implementing UI enhancements or API integrations
- Adding support for additional sign languages (ASL/ISL/BSL)
- Improving dataset collection, data augmentation, or pipeline modularity

To contribute, open a Pull Request or create an Issue with your proposal.


## License

Licensed under the MIT License, allowing full flexibility to reuse, modify, distribute, and integrate this project into personal or commercial applications. Attribution is required.


## Contact

If you have questions, suggestions, or collaboration ideas, feel free to reach out at:
📩 akashgpatil23.05@gmail.com

























