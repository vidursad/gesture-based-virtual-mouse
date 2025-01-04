# gesture-based-virtual-mouse

![Screenshot (94)](https://github.com/user-attachments/assets/62b3124b-618f-4ac1-9963-0c56cf52d306)
![Screenshot (97)](https://github.com/user-attachments/assets/81fd50ab-1923-4914-a754-d85f8ad0cfdd)

The Machine Learning Virtual Mouse project combines computer vision and machine learning techniques to develop a system that allows users to control a computer cursor using hand gestures. This project eliminates the need for a physical mouse, enhancing accessibility and offering a touchless interface, particularly useful in hygienic or remote operation scenarios.

Key Features

Hand Gesture Recognition:

Recognizes specific hand gestures (e.g., single finger for movement, pinch for clicking).
Implements dynamic and static gestures to control various actions like left-click, right-click, drag-and-drop, and scrolling.
Real-Time Tracking:

Tracks hand movement in real time using a webcam or other camera device.
Maps the detected hand position to the screen coordinates for smooth cursor control.
Touchless Interaction:

Offers a touch-free alternative to traditional input devices, promoting hygiene and accessibility.
Cross-Platform Compatibility:

Can work on multiple platforms, including Windows, macOS, and Linux, with appropriate configurations.
Technologies Used
Computer Vision:

Utilized OpenCV for image processing and detecting hand contours.
Extracts features like finger positions and gestures from the camera feed.
Machine Learning:

Employs pre-trained models or custom models for gesture classification.
Frameworks like TensorFlow or PyTorch can be used for creating and training the model.
Mediapipe (Optional):

For efficient hand tracking and gesture recognition using Google's pre-trained models.
Python Programming:

Core language for integrating different modules and handling camera input/output.
Integration Tools:

PyAutoGUI for controlling the system cursor based on gesture inputs.
Other libraries for implementing advanced functionalities like virtual keyboard support.
How It Works
Input Capture:

A webcam captures the user's hand movements.
Preprocessing:

Frames are processed to identify the Region of Interest (ROI), which is the area containing the hand.
Filters like Gaussian blur or thresholding are applied to enhance detection accuracy.
Gesture Detection:

Features such as finger count, convex hull, or hand landmarks are extracted.
The extracted features are fed into a trained ML model to classify gestures.
Cursor Mapping:

The system maps hand movements to the screen coordinates.
Detected gestures trigger actions like mouse clicks or scrolls.
Output:

The cursor responds in real time to gestures, offering seamless interaction.
