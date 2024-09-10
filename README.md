# Sign Language Recognizer

![Sign Language Recognizer](images/logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [API Deployment](#api-deployment)
- [Dataset](#dataset)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Sign Language Recognizer is a machine learning-based application designed to interpret sign language gestures and translate them into text or speech. The application leverages computer vision and deep learning techniques to enable communication between deaf individuals and others. It can be deployed as a web application or integrated into other apps via an API.

[Download the complete project here](https://drive.google.com/drive/folders/1s9g8vJnp20Zuj18soJRqtv5uIe7baIPQ?usp=share_link)

## Features

- Real-time sign language gesture recognition
- Supports multiple sign language gestures
- Customizable to support new gestures
- Web-based user interface
- API support for easy integration with other applications
- Uses TensorFlow and OpenCV for model training and prediction

## Installation

To run the Sign Language Recognizer locally, follow these steps:

1. **Clone the repository:**

    ```bash
    [git clone https://github.com/y/sign-language-recognizer.git](https://github.com/aniket-singh-01/SignLanguage.git)
    cd SignLanguage
    ```

2. **Set up a Python virtual environment:**

    ```bash
    python3 -m venv funEnv
    source funEnv/bin/activate
    ```

3. **Run the application:**

    ```bash
    cd Sign/WebApp
    flask run
    ```

## Usage

Once the application is running, open your browser and navigate to `http://localhost:5000`. The web interface will allow you to upload videos or use your webcam for real-time sign language recognition.

