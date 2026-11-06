# Affectra-Decode Your Stress Web Application
# 🧠 Stress Detector Web Application

A web-based stress detection application that analyzes facial movements using a webcam to estimate stress levels. The system categorizes stress into calm, tensed, and highly stressed states and provides useful feedback to the user.

---

## ✨ Features

- Live webcam-based stress detection
- 30-second automatic stress analysis
- Start and Stop camera controls
- Stress level classification:
  - 🙂 Calm / Smiling → 0–40%
  - 😐 Tensed → 50–70%
  - 😣 Highly stressed / excessive blinking → 80–100%
- Color-coded stress indicator
- Stress reduction suggestions
- Average stress calculation
- Last check timestamp
- History of last 20 stress records
- Dark theme user interface

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python, Flask  
- **Computer Vision:** MediaPipe  
- **Database:** SQLite  
- **Libraries:** NumPy, PIL  

---

## 📁 Project Structure

StressDetector/
│
├── app.py
├── stress.db
│
├── templates/
│ ├── index.html
│ ├── history.html
│ └── settings.html
│
├── static/
│ ├── style.css
│ └── script.js
| |___chart.js
| |___requirements.txt

🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Sayee2006/StressDetector.git
   cd StressDetector
Install dependencies:
Copy code
pip install flask flask-sqlalchemy mediapipe numpy pillow pytz

Run the application:
Copy code
python app.py
Open in browser:
Copy code
http://localhost:5000

How It Works
The webcam captures video frames for 30 seconds
Facial landmarks are detected using MediaPipe
Facial movement intensity is analyzed
Stress level is calculated based on movement patterns
Results are displayed with suggestions and saved to history

Note
This project is for educational purposes only and is not intended for medical diagnosis.

visit Link Here -> https://stress-detector-deploy-1.onrender.com/

Author
Developed by Sayee Arwalkar,Akanksha Parkhe,Pawani Gahoi

## 📜 License
This project is licensed under the MIT License.

