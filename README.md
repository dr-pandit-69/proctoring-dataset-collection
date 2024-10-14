# Online Examination AI Proctoring System Dataset Collection for Research

![System Demo](https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExa3drOHcwNnBicWF3cWlkbXRyM24wbmtjZm1lNGJ0N2V4c2hmdms5biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/YUVs6lIV0HAFzWqKea/giphy.gif)

(My webcam isn't connected in this demo, hence it is blank, Webcam & Mic selection to be done in browser)

Chrome Browser is recommended for this system

This project implements the dataset recording for proctoring system designed to monitor exam sessions through webcam and screen recording. 

## Features

- **User Authentication**: Secure login and registration functionality.
- **Webcam and Screen Recording**: Records both webcam feed and screen activity during the exam.
- **Time-Based Auto Submission**: Automatically submits the exam once the timer expires.
- **Consent-Based Recording**: Ensures the user gives consent before recording starts.
- **Data Submission**: After completing the exam, recordings and answers are securely submitted to the backend.
- **Post-Exam Cleanup**: Clears all sensitive data such as recordings, answers, cookies, and local storage after submission.

## System Components

1. **Frontend**:
   - Built using React, Material UI for styling, and React Router for navigation.
   - The recording functionality captures 720p resolution video and screen activity.
   - Timer-driven system to submit the exam automatically when the time is up.

2. **Backend**:
   - A Flask-based backend handles user authentication, question retrieval, and recording submissions.
   - Supports handling and storing recordings and exam data in a scalable and secure way.

## Installation and Setup

### Prerequisites
- Python that's it 

### Step 1: Clone the Repository

```bash
git clone https://github.com/dr-pandit-69/proctoring-dataset-collection.git
cd proctoring-dataset-collection
```

### Step 2: Create Virtual Environment (Optional, But Highly Recommended)

```bash
python -m venv .venv
.venv/scripts/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Initialize the Databases

```bash
python create_db.py
python feed_ques_db.py
```


### Step 5: Run The Project

```bash
python app.py
```

# Acknowledgment: If you use this system to collect data for any research work, I kindly request that you credit me for its contribution. Your acknowledgment would be greatly appreciated.






