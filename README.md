# Bicep Curl Counter using Mediapipe, OpenCV, and Python
This project demonstrates a Bicep Curl Counter implemented using the Mediapipe Pose model, OpenCV, and Python. By utilizing the powerful capabilities of the Mediapipe Pose model, we can identify the coordinates within the human body, while OpenCV enables us to capture the webcam feed.

The Mediapipe Pose model provides us with 33 landmarks, representing various parts of the body. We leverage these landmarks to identify the connections between different body parts. Specifically, we focus on the shoulder, elbow, and wrist landmarks to calculate the angle formed by the arm during a bicep curl exercise.

Here's how the process works:

1. We utilize OpenCV to capture the video feed from the webcam.
2. Using the Mediapipe Pose model, we detect and extract the landmarks for each frame of the video.
3. The connections between specific landmarks representing the shoulder, elbow, and wrist are identified.
4. Based on the identified landmarks, we calculate the angle formed by the arm using appropriate mathematical techniques.
5. The angle is then compared to a predefined threshold to determine if a bicep curl rep has been completed successfully.
6. The count of successfully completed bicep curls is updated and displayed on the screen.

To run this project locally, make sure you have Python installed along with the necessary libraries: Mediapipe and OpenCV. 

