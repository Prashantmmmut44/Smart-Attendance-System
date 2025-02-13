Facial Recognition Automatic Attendance Syste

Overview

This project is a facial recognition-based automatic attendance system that leverages OpenCV for efficient face detection and recognition. It streamlines attendance tracking by automatically recording user attendance upon facial recognition.

Features

Advanced Facial Recognition: Uses OpenCV's Haar cascade classifier and a trained model for accurate face recognition.

Automated Attendance Logging: Captures and records attendance in real-time, reducing manual effort.

Secure User Authentication: Implements a login system to ensure only authorized users can access the system.

Intuitive Graphical User Interface (GUI): A user-friendly interface designed for ease of use.

Data Storage: Stores attendance records efficiently using SQLite or CSV files.

Installation

Prerequisites

Ensure you have Python installed (preferably 3.7+). Install the required dependencies using:

pip install -r requirements.txt

Running the Project

Clone the repository or download the project files.

Navigate to the project directory.

Run the main script:

python main_project.py

Project Structure

main_project.py - Main script to launch the system.

main_login.py - Handles user authentication and security.

attendance.py - Manages and records attendance logs.

haarcascade_frontalface_default.xml - Pre-trained model for face detection.

classifier.xml - Trained model for facial recognition.

help.py, developer.py - Additional utility scripts.

Various .ico files - Icons for enhancing the UI aesthetics.

Technologies Used

Python (OpenCV, NumPy, Pandas, Tkinter)

OpenCV (Efficient face detection and recognition)

Tkinter (GUI development for an interactive experience)

SQLite / CSV (Reliable data storage for attendance tracking)

Future Enhancements

Enhance accuracy using deep learning models such as CNNs.

Implement cloud-based attendance tracking for remote accessibility.

Develop a mobile application for seamless integration.

Contributors

Prashant Srivastava
