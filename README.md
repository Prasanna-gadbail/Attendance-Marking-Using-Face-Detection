# Attendance-Using-Face-Detection*
************************************************Overview********************************************************
This project automates attendance marking using facial recognition with the Local Binary Patterns Histogram (LBPH) algorithm for face recognition and Haar Cascade for face detection. The system captures faces via webcam, detects them in real-time, and identifies individuals using a pre-trained model. Attendance is automatically recorded into a CSV file, eliminating the need for manual attendance tracking.

***********************************************Features**********************************************************
Face Detection with Haar Cascade: Uses OpenCV's Haar Cascade algorithm to detect faces in real-time.
Face Recognition with LBPH: Identifies individuals using the Local Binary Patterns Histogram (LBPH) algorithm, known for its robustness in facial recognition even in varying lighting conditions.
Automated Attendance Marking: Logs recognized faces along with a timestamp in a CSV file for easy tracking.
User-Friendly Interface: Includes a simple Tkinter-based graphical interface to make the system more accessible.

**********************************************How It Works********************************************************
Face Detection: The camera captures the image, and the Haar Cascade algorithm is used to detect faces in real-time.
Face Recognition: Once a face is detected, the LBPH algorithm compares the detected face with the faces in the database to recognize the individual.
Attendance Recording: When the face is recognized, the system automatically logs the name, date, and time in a CSV file.
Data Management: Attendance records are saved in a CSV file and can be exported for reporting purposes.
************************************************Requirements**********************************************************
Python 3.x
OpenCV
NumPy
Pandas
Tkinter (optional for GUI)
Pre-trained face recognition data using LBPH algorithm

***********************************************************************************************************************

	steps you have to follow
	Download or clone my Repository to your device
	type pip install -r requirements.txt in command prompt(this will install required package for project)
	Create a TrainingImage folder in a project folder.
	open Attendance.py and AutoAttendance.py, change all the path accoriding to your system
	Run AttendanceMarkup.py file
