
# Real-Time Facial Expression Detection using Mediapipe and OpenCV

This project demonstrates a real-time facial expression recognition system using Mediapipe FaceMesh and OpenCV. It detects and categorizes facial expressions based on geometric relationships between facial landmarks and visualizes the results with a user-friendly interface.




## Features


- Facial Landmark Detection:
  Identifies and tracks up to 468 facial landmarks in real time   using Mediapipe's FaceMesh.

- Expression Recognition:
  Classifies expressions into categories like:
   - Neutral
   - Smiling
   - Surprised
   - Angry

- Visual Feedback:
  Displays live webcam feed alongside a plotted visualization of detected facial landmarks.

- Real-Time Analysis:
  Processes video frames at runtime for immediate feedback on detected expressions.
## Use Cases

(1) - Human-Computer Interaction:
Emotion-aware systems for personalized user experiences.

(2) - Retail and Marketing:
Analyze customer reactions to products or advertisements.

(3) - Healthcare and Therapy:
Non-intrusive emotional state monitoring.

(4) - Education:
Evaluate student engagement during e-learning sessions.
## Technologies Used

- OpenCV:
For video capture and image display.

- Mediapipe:
Provides FaceMesh for facial landmark detection.

- NumPy:
Used for geometric calculations between landmark points.


## How It Works

1. Capture Video:
Uses OpenCV to stream live video from a webcam.

2. Detect Landmarks:
Mediapipe FaceMesh identifies facial landmarks in real time.

3. Analyze Expressions:
Calculates distances between key landmarks (e.g., eyes, lips) to determine expressions.

4. Visualize Results:
Displays the webcam feed and a blank canvas highlighting the detected landmarks.
## Installation


Install dependencies:

```bash
  
  pip install opencv-python mediapipe numpy
  

```
    
