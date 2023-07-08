#Virtual Mouse
"# VirtualMouse

## Description

VirtualMouse is an application that utilizes AI-based technology to control the mouse cursor through hand gestures. Its primary objective is to manage computers and other devices without the need for direct pointing, clicking, or touching the display. This application is particularly useful for individuals who are not comfortable using a touchpad or physical mouse. Additionally, VirtualMouse can be integrated into various games and other AI applications that rely on user-defined gestures for control.

With VirtualMouse, users can perform functions such as minimizing and maximizing the screen, copying, pasting, cutting, and other actions typically executed through a physical mouse. The application employs a real-time camera to detect hand landmarks and track gesture patterns made by the user. Once the user's hand is detected in the camera view, the application draws a bounding box around it. Specifically, the VirtualMouse detects movements of the index finger and middle finger, and responds accordingly. The mouse cursor moves when the index finger is raised, and a click operation is generated when both the index finger and middle finger are raised and positioned at a specific distance from each other or are touching.

VirtualMouse is implemented as a Python application and consists of two Python scripts: 'HTM.py' and 'Mouse.py'. The 'HTM.py' script tracks hand gestures, draws hand landmarks and edges, and contains the Hand Detector Class along with methods such as 'findhands()', 'findPosition()', 'fingersUp()', and 'findDistance()'. The 'Mouse.py' script utilizes the 'HTM.py' to detect hand movements and respond accordingly. It employs the 'pyautogui' package to simulate mouse functionality.

Python libraries used in VirtualMouse:

1. OpenCV:
    - OpenCV (Open Source Computer Vision Library) is an open-source software library for computer vision and machine learning tasks. It is used in VirtualMouse to access the real-time camera (webcam), perform drawing operations, and process images.

2. Mediapipe:
    - Mediapipe is an open-source framework developed by Google for media processing. In the context of VirtualMouse, Mediapipe Hands is used to achieve high-fidelity hand and finger tracking. It utilizes machine learning techniques to infer 21 3D landmarks of a hand.

3. Pyautogui:
    - PyAutoGUI is a Python automation library that enables various mouse control operations such as clicking, dragging, scrolling, and moving. It is utilized in VirtualMouse to control mouse movement and perform clicks.

Please note the following:

- Only one hand should be used to interact with the computer using VirtualMouse.
- For optimal performance, only the index finger and middle finger should be used.
- VirtualMouse is still in the initial stages of development and is undergoing maintenance and improvements. As a result, the application may not provide a seamless experience at this stage. However, you have the flexibility to modify and enhance the code according to your requirements.
  
For more information
you contact me 
WhatsApp : +260 97018 7487
Email : zimbaisaacj2002@gmail.com
Facbook: [Zimb Dev](https://www.facebook.com/Zimbapythondev)
