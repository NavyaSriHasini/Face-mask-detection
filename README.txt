Face Mask Detection using Deep Learning (Keras)

Project Title:
---------------
Real-time Face Mask Detection using Webcam Input

Author:
-------
Name: ATTILI NAVYA SRI HASINI  
Roll No: 240101076
Course: AI

Project Description:
---------------------
This project uses deep learning to detect whether a person is wearing a face mask or not in real time using webcam video feed. It uses a Convolutional Neural Network (CNN) built with Keras.

Project Structure:
------------------
mask_detection_project/
├── train_model.py              # Trains the CNN model on mask/no-mask dataset
├── detect_mask_video.py        # Uses webcam to detect masks in real-time
├── dataset/
│   ├── train/
│   ├── test/
│   └── validation/
└── README.txt                  # Instructions and project description

How to Run:
-----------
1. Open VS Code and navigate to the project folder.
2. Make sure you have Python installed (version 3.10+ recommended).
3. Install required libraries:
   pip install tensor flow keras opencv-python numpy

4. Step 1: Train the model
   Run this command:
       python train_model.py

   This will create a file called `mask_detector_model.h5`.

5. Step 2: Run real-time detection
   Run:
       python detect_mask_video.py

   A window will open showing webcam feed and % of Mask / No Mask for each detected face.

Libraries Used:
---------------
- Keras
- TensorFlow
- OpenCV (cv2)
- NumPy

Dataset:
--------
The dataset is not included in this repository due to size limitations.

Download dataset from:
[https://drive.google.com/drive/folders/1N1i5EaHKSQxcIIamreKcCw2iCSEsDXyP?usp=drive_link]

Used a labeled dataset with 'with_mask' and 'without_mask' images, organized into train/test/validation folders.

Output:
-------
The webcam window displays:
- Face bounding box
- Whether mask is detected
- Confidence percentages


Submitted By:
-------------
ATTILI NAVYA SRI HASINI



