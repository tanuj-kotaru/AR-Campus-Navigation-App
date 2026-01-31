# AR-Based Campus Navigation App

## Project Description
This project focuses on developing an **Augmented Reality (AR)–based campus navigation application** that helps students, staff, and visitors easily find locations within a college campus. The app overlays real-time navigation directions onto the live camera view, providing an intuitive navigation experience similar to Google Maps Live View, customized for campus use.

---

## Problem Statement
Large college campuses often make navigation difficult for new students and visitors. Traditional methods such as signboards, static maps, or verbal guidance are inefficient and confusing. Existing map applications do not provide accurate, campus-specific navigation, especially for walking paths. This leads to time loss, confusion, and inconvenience.

---

## Solution Overview
To address this problem, we propose an **AR-based campus navigation system** that visually guides users to their destination using real-time augmented reality directions. By combining mobile sensors, GPS, and AR technology, the app provides step-by-step navigation directly overlaid on the real-world environment through the phone camera.

---

## Features
- AR-based real-time navigation using camera view  
- Campus-specific location search (blocks, labs, offices, etc.)  
- Outdoor navigation with visual directional arrows  
- User-friendly and intuitive interface  
- Real-time direction updates as the user moves  

---

##  Technologies Used
- **Unity Engine**
- **AR Foundation**
- **ARCore (Android)**
- **Android SDK**
- **GPS & Device Sensors**
- **Firebase / JSON (for location data)**
- **Git & GitHub** (version control)

---

##  System Architecture (Overview)
The system consists of a mobile application integrated with an AR engine. The phone camera captures the real-world view, while GPS and sensor data determine the user’s position and orientation. Based on the selected destination, navigation logic calculates the direction and distance, and AR arrows are overlaid onto the camera feed to guide the user in real time.

---

##  Folder Structure
AR-Campus-Navigation-App/
│
├── unity-project/
│ ├── Assets/
│ ├── Scripts/
│ ├── Scenes/
│
├── assets/
│ └── 3D models, icons, AR arrows
│
├── datasets/
│ └── campus_locations.json
│
├── documentation/
│ ├── Project_Report.pdf
│ └── PPT/
│
├── README.md
└── .gitignore
