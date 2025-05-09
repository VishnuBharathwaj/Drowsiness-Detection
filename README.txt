# Drowsiness Detection System using Eye Aspect Ratio (EAR)

This Python project detects drowsiness in real time using a webcam feed. It uses facial landmark detection to monitor the user's eye aspect ratio (EAR), and triggers an alarm if drowsiness is detected based on eye closure.

## Features
- Real-time eye detection using dlib's 68-point facial landmarks
- Eye aspect ratio (EAR) calculation for drowsiness detection
- Buzzer alert using a sound file when drowsiness is detected
- Visual indication via bounding boxes and alert text

## Requirements
- Python 3.x
- Required libraries:
  - 'opencv-python'
  - 'dlib'
  - 'imutils'
  - 'scipy'
  - 'pygame'
  - 'numpy'

## Files Needed
- 'Drowsiness_Detection.py': Main Python script
- 'shape_predictor_68_face_landmarks.dat': Pre-trained facial landmark model
- 'haarcascade_frontalface_default.xml': Haar cascade for face detection
- 'music.wav': Alarm sound played on drowsiness detection

## How to Run
1. Install dependencies & required libraries.

2. Place all required files in the same directory.

3. Run the script: "python Drowsiness_Detecion.py" in the terminal.

4. Press 'Q' to quit the webcam window.

## Notes
- Ensure good lighting for better face and eye detection.
- Adjust 'EYE_ASPECT_RATIO_THRESHOLD' in the code based on your face and camera.
- You can view EAR values in the terminal to calibrate it properly.

## Credits
This project uses the dlib library developed by Davis E. King and OpenCV.

