# Real-Time Drowsiness Alert System
This project is a real-time drowsiness detection system using a webcam. It leverages computer vision and deep learning to monitor a user's facial features and raise an alert if signs of drowsiness are detected.

## Features
* Face and Eye Detection: Uses Haar cascades for detecting faces and eyes in real-time.
* Deep Learning Model: Classifies eye states (open/closed) using a pre-trained CNN model.
* Alert System: Triggers an alarm if the user appears drowsy for a prolonged period.
### Files Included
. CP2 Drowsiness Alert System data preprocessing and model building.ipynb
Contains the data preprocessing and model training workflow. It demonstrates how the dataset was prepared and the CNN model was trained for eye state classification.

2. CP2 Real Time Drowsiness Alert using Webcam.ipynb
Implements the real-time drowsiness detection system using the trained model and a webcam.

3. drowsiness_detection_model.h5
Pre-trained deep learning model used for eye state classification.

## Usage
Train the Model
To understand or modify the training process, open and run the CP2 Drowsiness Alert System data preprocessing and model building.ipynb notebook.

## Run the Real-Time Detection
1. Open the CP2 Real Time Drowsiness Alert using Webcam.ipynb notebook.
2. Execute the cells to start the webcam-based drowsiness detection system.
3. Alert Mechanism
4. If the system detects that both eyes are closed for a prolonged period:

* A visual alert is displayed.
* An audible alarm is triggered to grab the user's attention.
## Requirements
Python 3.7+
OpenCV 4.x
TensorFlow/Keras
Numpy
Pygame (for audio alert)
## Future Enhancements
Integration with mobile or embedded devices.
Support for more complex scenarios (e.g., multiple faces, head pose detection).
Incorporation of additional features like blinking rate or yawning detection.

