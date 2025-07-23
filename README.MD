# 🖐️ Hand Gesture Recognition System

This project is an AI-powered real-time **Hand Gesture Recognition System** built using computer vision and machine learning. It captures hand gestures through a webcam or CCTV stream and classifies them into predefined categories. The system can be extended for gesture-controlled interfaces, smart surveillance, or touchless applications.

## 📸 Features

- Real-time gesture detection using OpenCV
- Supports predefined hand gestures (e.g., palm, fist, thumbs-up)
- Live video stream support via webcam or RTSP
- Easily expandable with new gesture training
- Lightweight and fast for real-world deployment

## 🧠 Tech Stack

- Python
- OpenCV
- NumPy
- Scikit-learn (or TensorFlow/Keras if using deep learning)
- MediaPipe (for accurate hand landmark detection)
- Flask (optional, if integrated with web interface)

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
Create a virtual environment and activate it (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🧪 Usage
Run the following command to start the hand gesture recognition system:

bash
Copy
Edit
python hand_gesture.py
You can configure it to use either a webcam or an RTSP stream by modifying the video capture source in the code:

python
Copy
Edit
cv2.VideoCapture(0)  # For webcam
cv2.VideoCapture("rtsp://your-stream-url")  # For CCTV/RTSP
📂 Project Structure
bash
Copy
Edit
hand-gesture-recognition/
│
├── hand_gesture.py           # Main script
├── model/                    # Trained model (if applicable)
├── gestures/                 # Labeled gesture image dataset
├── requirements.txt          # Python dependencies
├── README.md                 # Project description
└── assets/                   # Screenshots or visual aids
📷 Sample Output
Palm Gesture	Fist Gesture	Thumbs-Up

🚀 Future Improvements
Add dynamic gesture recognition (like waving, pointing)

Integrate voice or GUI feedback

Connect with IoT for gesture-based home automation

Train on custom gestures with a CNN model

🤝 Contributing
Pull requests are welcome! If you find bugs or want to add features, feel free to fork the repo and submit a PR.