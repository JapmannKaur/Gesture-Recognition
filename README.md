# Gesture-Recognition

## Prerequisite
Install mediapipe:
**pip install mediapipe**

## Mediapipe
Mediapipe uses ML Pipeline consisting of:
* **Palm detection model** that recognizes the hand and returns the boundaries
* **Hand landmark model** that operates on the output defined by the above model and returns high-fidelity 3D hand keypoints. 

## Random Forest
Random Forest classifier is used to classify the gestures returned by the mediapipe model into various categories like love, niceday, wake, funny, sorry, etc depending upon the dataset defined by the user
