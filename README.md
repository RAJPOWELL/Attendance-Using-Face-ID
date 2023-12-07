# Face Recognition Attendance System

## Overview

The Face Recognition Attendance System is a project designed for automating attendance tracking using facial recognition technology. The system detects faces in a video stream, recognizes individuals by comparing them with a pre-existing database, and updates attendance records in a SQLite database. It also includes a web application built with Flask to visualize attendance data.

## Features

- **Face Detection:** Utilizes Dlib's frontal face detector to locate faces in a video stream.
- **Facial Landmarks and Recognition:** Utilizes Dlib's shape predictor and ResNet model to extract facial landmarks and compute 128D face descriptors.
- **Database Integration:** Stores facial features and attendance records in an SQLite database.
- **Web Application:** Provides a user interface to view attendance records based on selected dates.

## Installation

1. Clone the repository:
	bash```
		git clone https://github.com/RAJPOWELL/A-ML-.git```

2. Navigate to the project directory:
	bash```
		cd FRS```
	
3. Install the requirements file:
	bash```
		pip install -r requirements.txt```
	
4. Execute the Flask app
	bash```
		Python app.py```

## Dependencies
-Flask
-Dlib
-OpenCV
-NumPy
-Pandas


