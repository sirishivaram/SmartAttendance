Smart Attendance System using Facial Recognition

This project is a Python-based Smart Attendance System that uses facial recognition to automatically record attendance. It leverages OpenCV and the `face_recognition` library to detect and recognize faces from a webcam feed.

## 📁 Project Structure

SmartAttendance/
├── scripts/ # Python scripts for capturing, encoding, and recognizing faces
├── dataset/ # Stored face images for registered users
├── encodings/ # Pickled facial encodings
├── attendance/ # Excel/CSV logs of attendance
├── requirements.txt # Python dependencies
└── README.md # Project documentation

markdown
Copy
Edit

## 💡 Features

- Face detection and recognition using `face_recognition`
- Stores captured face images in `dataset/`
- Encodes faces and stores in `encodings/`
- Detects registered and unknown faces
- Records attendance in CSV with Name, Date, and Time
- Avoids false positives and duplicate entries

## 🛠️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/sirishivaram/SmartAttendance.git
   cd SmartAttendance
Create a virtual environment (recommended):

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate  # On Windows
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt

🚀 Usage
Capture New Faces:

bash
Copy
Edit
python scripts/capture_images.py

Encode Faces:

bash
Copy
Edit
python scripts/encode_faces.py
Run Attendance System:

bash
Copy
Edit
python scripts/recognize_faces.py

📦 Requirements
See requirements.txt or install directly:

bash
Copy
Edit
pip install opencv-python face_recognition numpy pandas

🙌 Acknowledgements

OpenCV

face_recognition

Dlib
