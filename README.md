# Sign Language Recognition using Deep Learning and Computer Vision

Real-time vision-based Sign Language Recognition system designed to assist individuals with hearing and speech impairments by translating hand gestures into readable text. This project aims to promote accessibility and inclusivity by bridging communication gaps.

# Project Overview

The system recognizes six basic sign gestures:

1. Hello

2. How are you

3. I’m sorry

4. Thank you

5. I love you

6. Goodbye

We used deep learning techniques with Long Short-Term Memory (LSTM) networks and MediaPipe Holistic keypoint detection to achieve accurate gesture recognition in real-time.

# Problem Statement

Individuals with hearing or speech impairments often rely on sign language, which is not universally understood. This project addresses the need for a reliable, real-time sign language recognition system that can interpret gestures and output readable text without requiring human interpreters.

# Tools & Technologies

- Python

- OpenCV (cv2)

- MediaPipe Holistic

- TensorFlow & Keras

- NumPy, Sci-kit Learn, Matplotlib

# Methodology

1. Keypoint Detection with MediaPipe Holistic

- Extracted body, face, and hand landmarks (540+ points)

2. Dataset Creation

- Captured 30 videos per gesture (30 frames each)

- Converted sequences into TensorFlow-compatible format

3. Data Preprocessing & Labeling

- Split into training and testing sets

- One-hot encoding of gesture labels

4. Model Architecture

- 3 LSTM layers

- 2 Dense layers with ReLU activation

- Final Dense layer with Softmax activation

- Trained using Adam optimizer & categorical crossentropy

5. Model Evaluation

- Achieved categorical accuracy of ~79% during training

- Evaluated with Confusion Matrix and Accuracy Score

6. Real-time Testing

- Integrated OpenCV and MediaPipe for live gesture detection and text output

# Contributors

- Krittika Sardar

- Anjali Sinha

- Bobby Baidya

Supervised by Dr. Soham Sarkar
