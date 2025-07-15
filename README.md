Smart Door Lock System with Face Recognition using Raspberry Pi
With the growing need for secure and intelligent access control solutions, this project presents the implementation of a smart door lock system using Raspberry Pi and real-time face recognition. Traditional locking mechanisms, including mechanical keys and PIN-based systems, are increasingly vulnerable to duplication and unauthorized access. This system offers a reliable and contactless alternative.

Key Features
Real-time face detection and recognition using OpenCV and the face_recognition library

Automatic door unlocking via servo or solenoid motor upon successful face identification

Automatic re-locking after a predefined time interval

Denies access to unrecognized users with optional image logging and alert notifications (via email or Telegram)

Flask-based web interface for user registration, monitoring access logs, and manual lock control

Technologies Used
Raspberry Pi (as the central processing unit)

Python, OpenCV, and face_recognition for image processing and recognition

Servo motor or relay module for door control

Flask framework for the web interface

Optional integration with email or Telegram for alert notifications

Applications
Smart home automation

Office access control systems

Hostel or dormitory room entry systems

Restricted area access in industrial or research environments
