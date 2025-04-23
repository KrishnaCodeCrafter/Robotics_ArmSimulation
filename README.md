# Fruit-Detection-Robot-with-OpenCV-and-Webots
This project demonstrates a fruit detection system using OpenCV for image processing and Webots for simulating robotic arm control. The system uses computer vision to identify objects, and a simulated robotic arm in Webots performs actions like picking and dropping fruits.
Fruit Detection Robot with OpenCV and Webots
Overview
This project combines computer vision and robotics to simulate a robotic arm that detects and interacts with fruits (apples and oranges) in a virtual environment. Using OpenCV for real-time image processing, the robot can identify fruits based on color and shape, and a Webots simulation controls the robotic arm to perform tasks such as picking and dropping fruits.

# Key Features
Real-time Fruit Detection: Detects apples and oranges using OpenCV by color segmentation and contour analysis.
Simulated Robotic Arm: The Webots simulator controls the arm for fruit picking and dropping tasks.
Customizable: Easily extendable to detect other objects or to refine detection methods.
Performance Feedback: Displays detection information, including fruit counts, on the terminal and GUI.

# Technologies Used
Python: Main programming language.
OpenCV: For image processing and object detection.
Webots: Simulation environment for robotics.
Numpy: For image data handling and mathematical operations.

# Future Improvements
Improve fruit detection by using machine learning models.
Add more fruit types and refine detection methods to avoid false positives (like skin being detected as fruit).
Integrate the project with cloud platforms like Google Cloud or Azure for remote simulation control.
