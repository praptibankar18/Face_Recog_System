# Attendance_System-using-Face_Recognition
The Face Recognition Attendance System is a Flask-based application that utilizes face recognition technology to automate the process of marking attendance. It offers a convenient and efficient way to track attendance by identifying individuals based on their faces.

# Describe the model and working
The attendance system using face recognition captures images of individuals, detects and recognizes their faces in real-time using a pre-trained machine learning model, and records the attendance information in a database. The system automates the attendance tracking process, eliminates the need for manual record-keeping, and provides real-time attendance data.

# Experimentsl setup and dependencies for the project
This code is a simple attendance management system that uses face recognition to mark attendance. It is a Flask application that uses the OpenCV library for image processing and the scikit-learn library for machine learning.

# The dependencies required to run this code are
Flask  opencv-python (version 4.5.3.56) pandas (version 1.3.4) scikit-learn (version 1.0.2) joblib Additionally, the code also uses the haarcascade_frontalface_default.xml file for detecting faces, which is included in the OpenCV library. The code is a Python program that uses the Flask web framework to create a web application for facial recognition-based attendance management. Here are the main dependencies used in the code:

# Overiew of all libaries
OpenCV (cv2): A computer vision library used for face detection and image processing. Flask: A web framework for building web applications in Python. NumPy: A numerical computing library used for array processing and linear algebra operations. scikit-learn: A machine learning library used for K-nearest neighbors classifier for face recognition. Pandas: A data manipulation library used for reading and writing CSV files. Joblib: A Python library used for efficient serialization of Python objects.

# Installation of above deopendecies
Here are the steps to install the dependencies needed for the above code: Open a command prompt or terminal window on your computer.

Make sure you have Python installed on your computer. You can check by typing python --version in the command prompt or terminal window. If you don't have Python installed, you can download it from the official website: https://www.python.org/downloads/

Install the required packages using pip. Type the following command in the command prompt or terminal window: pip install numpy pandas matplotlib seaborn sklearn

Steps to Build a Face Recognition System Step 1: Install libraries

also we need to install 2 libraries in order to implement face recognition.

step2 : dlib: Dlib is a modern C++ toolkit containing machine learning algorithms and tools for creating complex software in C++ to solve real-world problems.

installing dlib pip install dlib face recognition: The face_recognition library, created and maintained by Adam Geitgey, wraps around dlib facial recognition functionality. step3 installing face recognition pip install face recognition

Opencv for some image pre-processing. step4 : installing opencv pip install opencv

# Dataset for the project
we want to recognize. These images should be clear and of high quality, with the faces of the individuals clearly visible. The dataset should contain a variety of images for each person, taken under different lighting conditions, angles, and facial expressions, to ensure that the face recognition algorithm is robust and accurate.

In this specific code, the dataset is assumed to be located in a folder named 'Images', and the code reads all the images in this folder and extracts the face encodings for each image using the face_recognition library. The images in the dataset should be named according to the name of the person in the image, as the code extracts the person's name from the image file name and uses it for attendance tracking.

# GUI for the project
The code implements a GUI for a face recognition attendance system using Flask. It allows users to view attendance records, add new users by capturing their face images, and take attendance by recognizing faces through the webcam. The system displays the attendance information on a web page and saves the records in CSV files.

# Performance Analysis:
Overall, the performance of the code can be affected by various factors such as the quality of the camera, the size of the face in the frame, the number of users and images in the "static/faces" folder, the disk speed, and the number of users accessing the web interface simultaneously. Therefore, it is recommended to test the code on different hardware configurations and environments to ensure optimal performance.

# Conclusion
In conclusion, an attendance system using face recognition can greatly simplify and streamline attendance tracking processes. By leveraging computer vision and machine learning techniques, the system can accurately and efficiently identify individuals and record their attendance. However, it is important to ensure the system is secure and respects individual privacy by adhering to data protection regulations. Overall, such systems have the potential to greatly improve attendance management in various settings such as schools, workplaces, and events.
