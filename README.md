# ESP32 CAM Object Detection and Image Storage

This project utilizes an ESP32 CAM module to capture images when an ultrasonic sensor detects an object. The captured images are then sent to a Firebase Storage bucket. Additionally, an HTML page is provided to view the stored images from Firebase.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is phase 1 of the prefinal academic project named "Object Detection and Identification". It involves:
1. Capturing an image using the ESP32 CAM module when an ultrasonic sensor detects an object.
2. Sending the captured image to a Firebase Storage bucket.
3. Providing an HTML page to view the stored images from Firebase.

## Features

- **ESP32 CAM Module**: Captures images upon detecting an object.
- **Ultrasonic Sensor**: Triggers the ESP32 CAM to capture images.
- **Firebase Storage**: Stores the captured images.
- **HTML Page**: Displays the stored images using CSS and JavaScript.

## Technologies Used

- **ESP32 CAM Module**
- **Ultrasonic Sensor**
- **Firebase Storage**
- **Arduino IDE**
- **HTML/CSS/JavaScript**

## Setup Instructions

### Hardware Setup

1. **ESP32 CAM Module**: Connect the ESP32 CAM to the ultrasonic sensor.
2. **Ultrasonic Sensor**: Ensure proper wiring between the ESP32 CAM and the ultrasonic sensor.

### Software Setup

1. **Arduino IDE**: Install the Arduino IDE and necessary libraries for ESP32 and Firebase.
2. **Firebase**: Create a Firebase project and set up a Storage bucket.
3. **ESP32 CAM Code**: Upload the provided code to the ESP32 CAM module via the Arduino IDE. Ensure you include your Firebase credentials and Wi-Fi details.
4. **HTML Page**: Develop an HTML page with CSS and JavaScript to fetch and display images from Firebase Storage.

## Usage

1. Power on the ESP32 CAM module.
2. The ultrasonic sensor will detect objects and trigger the camera to capture images.
3. Captured images will be sent to the Firebase Storage bucket.
4. Access the HTML page to view the stored images.

## Future Work

This project is phase 1 of "Object Detection and Identification". Future phases will include:
- Identification of image.
- if human is detected sending an alert through email.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request with detailed information on proposed changes.

---

This README provides an overview of the ESP32 CAM Object Detection and Image Storage project, including setup instructions and usage guidelines.

