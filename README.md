# SnapClass – AI-Powered Attendance Management System

SnapClass is an intelligent attendance management system designed to reduce the time teachers spend taking attendance manually.

Instead of calling students one by one or maintaining paper attendance sheets, teachers can use face recognition or voice recognition to record attendance. Students register their details in advance, allowing the system to identify them during attendance sessions.

## Live Links

- **Landing Page:** [SnapClass Landing Page](https://snap-class-landing-page-alpha-khaki.vercel.app/)
- **Live Web Application:** [Open SnapClass App](https://my-snapclass-project.streamlit.app/)

## Why SnapClass?

Taking attendance manually can consume valuable classroom time. Paper registers can also become difficult to manage and maintain.

SnapClass aims to make the process faster and more convenient by using AI-based biometric recognition.

## How It Works

### 1. Student Registration

Students can create an account and register their identity using:

- **Picture Registration:** Students provide a picture that can be used for face recognition.
- **Voice Registration:** Students provide a voice sample for voice recognition.

Their registration information is stored in the system for future identification.

### 2. Teacher Registration and Login

Teachers can sign up and log in using their name and password. After logging in, they can access the attendance dashboard, create subjects, and manage their attendance activities.

### 3. Face Recognition Attendance

When a teacher enters the classroom, they can capture approximately two or three pictures of the class or take group photos.

The system checks the detected faces against registered student data. When a student is successfully recognised, their attendance is marked automatically.

### 4. Voice Recognition Attendance

Teachers can also use voice recognition for attendance. The system processes student voices and compares them with registered voice samples to identify students and record their attendance.

## Main Features

- Separate signup and login for teachers and students
- Student registration using pictures and voice samples
- Teacher dashboard
- Subject creation and management
- AI-based face recognition attendance using classroom or group photos
- AI-based voice recognition attendance
- Automatic attendance marking for recognised students
- Attendance records for classroom sessions

## Technologies Used

SnapClass is developed using:

- **Python** – Application development
- **Streamlit** – Application interface
- **Deep Learning** – AI-based recognition
- **Face Recognition** – Identifying registered students from images
- **Voice Recognition** – Identifying registered students from voice samples

The project combines application development and deep learning to make classroom attendance more seamless.

## Project Goal

The goal of SnapClass is simple: help teachers spend less time managing attendance and more time teaching.

By using face and voice recognition, the system aims to replace time-consuming manual attendance with a faster, AI-assisted process.

## Important Note

Recognition accuracy depends on the quality of captured images and voice samples, as well as the performance of the recognition system. Attendance records should be reviewed whenever recognition results are uncertain.

Since SnapClass uses biometric information, student images, voice samples, and personal data should be handled responsibly and only with appropriate permission.