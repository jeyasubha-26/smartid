## Abstract  

This project implements a face recognition–based attendance management system using Python. The system leverages the Labeled Faces in the Wild (LFW) dataset for testing and applies the DeepFace library with the Facenet model to perform facial verification. The attendance process is automated by comparing a given test image with reference images in the dataset and marking individuals as either present or absent. The results are stored in a structured CSV file with timestamps for present entries.  

In addition to attendance logging, the system integrates an automated email notification feature using SMTP. After attendance is recorded, a list of absentees is compiled and sent to a specified email address. This approach demonstrates how computer vision and machine learning techniques can be combined with traditional communication protocols to create a scalable attendance solution. The framework can be extended to real-time applications by integrating with webcam feeds or deploying in classroom environments.  


## Project Description  

This project is a Python-based attendance system that uses face recognition for automated identification of individuals. It employs the DeepFace library with the Facenet model to verify faces against a dataset derived from the Labeled Faces in the Wild (LFW). Attendance records are stored in a CSV file, and an absentee list is automatically sent via email using SMTP. The system is modular and can be extended to support real-time webcam input or integrated into larger classroom management platforms.  
