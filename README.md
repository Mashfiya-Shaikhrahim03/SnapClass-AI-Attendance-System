# SnapClass – AI-Powered Attendance Management System

SnapClass is an intelligent attendance system designed to reduce the time teachers spend taking attendance manually.

Instead of calling students one by one or maintaining paper attendance sheets, teachers can use face recognition or voice recognition to record attendance. Students register their details in advance, so the system can identify them during an attendance session.

## Live Links

- **Landing Page:** [SnapClass Landing Page](https://snap-class-landing-page-alpha-khaki.vercel.app/)
- **Live Web Application:** [Open SnapClass App](https://my-snapclass-project.streamlit.app/)

## Why SnapClass?

Taking attendance manually can take valuable classroom time. Paper registers can also become difficult to manage and maintain.

SnapClass aims to make the process quicker and more convenient by using AI-based biometric recognition.

## How It Works

### 1. Student Registration

Students can create an account and register their identity using:

- **Picture registration:** Students provide a picture that can be used for face recognition.
- **Voice registration:** Students provide a voice sample for voice recognition.

Their registration information is stored in the system for later identification.

### 2. Teacher Registration and Login

Teachers can sign up and log in using their name and password. After logging in, they can access the attendance dashboard and manage their classes and attendance activities.

### 3. Face Recognition Attendance

When a teacher enters the classroom, they can take around two or three pictures of the class or capture a group photo.

The system checks the people detected in the pictures against the registered student data. When a student is recognised, the system marks that student's attendance.

### 4. Voice Recognition Attendance

Teachers can also take attendance using voice recognition. The system listens for registered student voices, identifies them against the stored voice data, and records attendance when a student is recognised.

## Main Features

- Separate signup and login for teachers and students
- Student registration using pictures and voice samples
- Teacher dashboard
- Subject creation and management
- AI-based face recognition attendance using classroom or group photos
- AI-based voice recognition attendance
- Automatic attendance marking for recognised students
- Attendance records for classroom sessions

## Technology

SnapClass is developed using:

- **Python** for application development
- **Streamlit** for the application interface
- **Deep Learning** for AI-based recognition
- **Face Recognition** for identifying registered students from images
- **Voice Recognition** for identifying registered students from voice samples

The project combines application development and deep learning to make classroom attendance more seamless.

## Project Goal

The goal of SnapClass is simple: help teachers spend less time on attendance and more time teaching.

By using face and voice recognition, the system aims to replace time-consuming manual attendance with a faster, AI-assisted process.

## Note

Recognition depends on the quality of the captured images or voice samples and the accuracy of the recognition system. Attendance records should be reviewed when a recognition result is uncertain.

Because the system uses biometric information, student data and voice or image samples should be handled carefully and only with appropriate permission.
"""

