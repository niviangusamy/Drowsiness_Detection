💤 Drowsiness Detection System
🚗 Overview
The Drowsiness Detection System detects driver fatigue using real-time video and alerts the driver to prevent accidents. It uses OpenCV for video processing and dlib for facial landmark detection to monitor eye closure.

📚 Requirements
Python 3.x
OpenCV
dlib
NumPy

🚀 Installation
1. Clone the repository:
git clone https://github.com/your-username/drowsiness-detection.git
cd drowsiness-detection
2. Install dependencies:
pip install -r requirements.txt
Download the shape predictor: Download shape_predictor_68_face_landmarks.dat from here and place it in the project folder.

📄 Usage
Run the script:
python drowsiness_detector.py
📂 Project Structure
📂 drowsiness-detection/
├── drowsiness_detector.py
├── shape_predictor_68_face_landmarks.dat
├── requirements.txt
└── README.md
🔔 Alert Mechanism
The system triggers an alert when it detects prolonged eye closure.

🤝 Contributing
Contributions are welcome! Feel free to submit a pull request.

📝 License
This project is licensed under the MIT License.

That's it! Let me know if you need help with the code or anything else! 😊
