# 🚀 Touchless Interaction with Kiosk

## 📖 Overview

**Touchless Interaction with Kiosk** is a computer vision and deep learning-based application that enables users to interact with a kiosk interface using **hand gestures** instead of physically touching the screen.

The system was developed to improve **hygiene, accessibility, and user experience** in public environments such as ATMs, ticket booking machines, airport check-in kiosks, hospitals, and other self-service systems.

Using **OpenCV**, **MediaPipe**, **TensorFlow**, and **Flask**, the application performs real-time hand detection and gesture recognition to provide a smooth, touch-free interaction experience.

---

## 🎯 Problem Statement

Traditional touchscreen kiosks require users to physically touch the display, which can:

- Increase the spread of germs in public environments.
- Create accessibility challenges for some users.
- Reduce convenience in high-traffic areas.
- Require frequent cleaning and maintenance.

This project solves these challenges by replacing physical touch with **real-time hand gesture recognition**, allowing users to operate the kiosk without making physical contact.

---

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **OpenCV**
- **TensorFlow / Keras**
- **MediaPipe**
- **NumPy**
- **HTML5**
- **CSS3**
- **JavaScript**

---

## ✨ Features

- 🎥 Real-time hand tracking using MediaPipe
- ✋ Gesture-based menu navigation
- 🖥️ Touch-free kiosk interaction
- ⚡ Lightweight and low-latency processing
- 🎯 More than **90% gesture recognition accuracy**
- 📷 Webcam-based interaction (no additional hardware required)

---

## 🧠 How It Works

1. The webcam captures live video frames.
2. OpenCV processes each frame in real time.
3. MediaPipe detects the user's hand and extracts hand landmarks.
4. The hand region is preprocessed before being passed to the trained TensorFlow model.
5. The gesture recognition model classifies the detected gesture.
6. Flask sends the recognized gesture to the frontend.
7. The kiosk interface performs the corresponding action, such as navigation or selection.

---

## 📂 Project Structure

```text
Touchless_Interaction_With_Kiosk/
│
├── app.py                  # Main Flask application
├── gesture_model.h5        # Trained TensorFlow model
├── requirements.txt
│
├── templates/
│   └── index111.html
│
├── static/
│   ├── styles.css
│   ├── styles1.css
│   ├── styles2.css
│   ├── *.png
│   └── *.jpg
│
└── README.md
```

---

## 🖥️ Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/touchless-kiosk.git
```

### Navigate to the Project Folder

```bash
cd touchless-kiosk
```

### Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

---

## 📦 Requirements

```text
Flask
opencv-python
tensorflow
mediapipe
numpy
```

---

## ⚠️ Challenges Faced

During development, the following challenges were encountered:

- Handling different lighting conditions.
- Reducing background noise and false detections.
- Improving gesture recognition accuracy.
- Minimizing processing delay for real-time interaction.
- Maintaining stable hand tracking under different camera angles.

---

## 📈 Results

- ✅ Achieved **over 90% gesture recognition accuracy** during testing.
- ✅ Successfully integrated real-time gesture recognition with the kiosk interface.
- ✅ Improved accessibility through touch-free interaction.
- ✅ Reduced the need for physical contact in public environments.
- ✅ Delivered smooth and responsive real-time performance.

---

## 🚀 Future Enhancements

- Dynamic gesture recognition
- Voice-assisted interaction
- Multi-language support
- Face authentication
- Cloud integration
- IoT-enabled smart kiosk support

---

## 📸 Screenshots

> Add screenshots of your project here.

Example:

```
screenshots/
├── home.png
├── gesture_detection.png
├── menu_navigation.png
```

---

## 👨‍💻 Author

**Hema Shankar**

If you found this project helpful, consider giving it a ⭐ on GitHub.
