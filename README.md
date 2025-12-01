# Hand Sign Gesture to Text Converter

## 🧠 Project Description  
This project captures hand gestures (signs) via webcam and converts them into text in real-time. It aims to help bridge the communication gap between sign-language users and people who do not understand sign language — providing an accessible, machine-vision based solution for gesture-to-text translation.

## Features  
- Real-time hand detection via webcam.  
- Recognition of predefined hand-sign gestures corresponding to letters/words.  
- Conversion of recognized gestures into human-readable text output.  
- (Optional/Future) Expandable gesture set — you can add custom gestures by collecting more training data.  

## Technologies Used  
- **Python** — main programming language.  
- **OpenCV** — for capturing video frames from webcam and image preprocessing.  
- (Optional) Any ML/DL libraries (if used) for gesture classification.  

## Project Structure  

/ — Root folder
├── Source code/ — Contains scripts for detection, classification, and gesture-to-text conversion
├── Training Data/ — Dataset of hand-gesture images used for training/testing
├── README.md — This file



> **Note:** The above structure assumes you have separated source code and training data. Adjust paths as per your actual repository layout.

## How to Use  

1. Clone the repository:  
   ```bash
   git clone https://github.com/prranavii/handsign-gesture-to-text-converter.git
   cd handsign-gesture-to-text-converter
pip install opencv-python numpy
python <your_main_script>.py

