# Gesture-Controlled-LED-Display-Using-Computer-Vision-and-Arduino

# Project Overview:

I recently completed an exciting project that integrates computer vision with hardware control, creating a real-time, gesture-controlled LED display system. This project involved using Python with OpenCV for hand tracking and finger detection, coupled with an Arduino to control a 7-segment LED display based on detected gestures.

#  Key Features:

# Real-Time Hand Tracking:

Implemented a hand tracking and finger detection system using OpenCV and the cvzone.HandTrackingModule.
The system captures live video from a webcam, identifies the number of fingers held up, and responds accordingly in real-time.

# Hardware Integration with Arduino:

Leveraged the pyFirmata library to interface Python with an Arduino board.
Controlled a 7-segment LED display connected to the Arduino, where specific hand gestures trigger different numerical displays.

# Gesture-Based Control:

The system detects specific hand gestures (e.g., the number of fingers raised) and maps them to corresponding numerical values displayed on the LED.
Each finger configuration directly controls which digit is displayed on the 7-segment display, making it an interactive and intuitive user interface.

# Challenges and Solutions:

Synchronization: Ensured smooth and real-time synchronization between the computer vision module and the hardware control to achieve seamless operation.
Accuracy: Fine-tuned the detection parameters to accurately recognize gestures under various conditions, ensuring reliable hardware response.

# Outcome:

This project showcases how computer vision and embedded systems can be combined to create responsive, gesture-based control systems. It has potential applications in interactive interfaces, digital counters, and more, demonstrating the power of integrating software with hardware for innovative solutions.

# Technologies Used:

Programming Language: Python

Libraries: OpenCV, cvzone.HandTrackingModule, pyFirmata, NumPy

Hardware: Arduino, 7-segment LED display, webcam
