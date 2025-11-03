# Week1
A sustainable AI-based attendance recognition system that uses Convolutional Neural Networks (CNNs) to automatically identify students from classroom images and mark attendance digitally. Promotes a continuous, paperless, and eco-friendly process.
Student Attendance Recognition Using CNN
🌱 Theme: Sustainability

This project focuses on developing a sustainable, paperless attendance system using Artificial Intelligence. The idea supports digital sustainability by reducing manual effort, saving time, and minimizing the use of physical resources like paper.

🧠 Project Concept

The project uses a Convolutional Neural Network (CNN) to recognize student faces from an image and automatically mark attendance. CNNs are powerful deep learning models capable of extracting spatial and visual features from images, making them ideal for face recognition tasks.

🧩 Problem Statement

Traditional attendance systems in educational institutions rely on manual entry, which is time-consuming and prone to errors. To address this, we propose an AI-based attendance recognition system using CNN-based face recognition that can automatically identify students from classroom images and record their attendance efficiently.
This approach promotes sustainability by enabling a continuous, digital, and eco-friendly attendance process.

📂 Dataset Description

The dataset consists of facial images of students collected manually for training and testing the recognition model.
Each student has a separate folder containing multiple face images.

Dataset structure:

dataset/
 ├── Deepika/
 │     ├── 1.jpg
 │     ├── 2.jpg
 ├── Sravani/
 │     ├── 1.jpg
 ├── Pranay/
 │     ├── 1.jpg

Each folder represents a student’s name, and the images inside are used for CNN-based face recognition training.

⚙️ Technologies Used

Python

OpenCV

DeepFace / Keras

CNN (Convolutional Neural Network)

NumPy, Pandas

🚀 Outcome

The system will take a classroom image as input, recognize students present using CNN-based facial recognition, and generate an automatic attendance report — ensuring accuracy, continuity, and sustainability in academic operations.
