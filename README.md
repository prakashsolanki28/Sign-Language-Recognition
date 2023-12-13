# Real-time Sign Language Recognition

This project aims to develop a real-time sign language recognition system using machine learning techniques. The system will be able to interpret sign language gestures captured through a video feed and convert them into corresponding text or speech.

# Images 
### Home Page of Frontend Design

![Home Page](./home_page.png)


## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)

## Introduction

In this project, we leverage computer vision and machine learning algorithms to recognize and interpret sign language gestures in real-time. The system utilizes a webcam or any other video input device to capture the gestures, which are then processed and classified by a trained machine learning model.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/real-time-sign-language-recognition.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download the pre-trained model weights (if available) and place them in the appropriate directory.
4. Run the main application: `python main.py`

## Usage

Once the application is running, it will start capturing video from the input device. To perform sign language recognition, simply make the corresponding gestures in front of the camera. The recognized text or speech output will be displayed or played back accordingly.

## Dataset

The sign language recognition model is trained on a custom dataset collected specifically for this project. The dataset consists of video recordings of various sign language gestures performed by different individuals. Each gesture is labeled with the corresponding text or speech output.

## Model Training

The machine learning model used for sign language recognition is trained using deep learning techniques. The architecture of the model is based on convolutional neural networks (CNNs) and recurrent neural networks (RNNs) to capture both spatial and temporal information from the input video frames.
