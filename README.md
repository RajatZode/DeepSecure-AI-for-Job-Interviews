DeepSecure — AI Deepfake Detector for Interviews

DeepSecure is an AI-powered system designed to detect deepfake or manipulated videos in online interviews. It analyzes facial consistency, texture, lighting, and behavioral patterns to identify suspicious activity in real time or recorded videos.

🎯 Features
🎥 Upload video or use live webcam
🧠 AI-based deepfake signal detection
👁️ Eye blink & facial landmark analysis (if available)
🎨 Texture + DCT artifact detection (GAN fingerprinting)
💡 Lighting consistency analysis
📊 Real-time risk scoring
🔔 Smart alerts (ding for genuine, alarm for suspicious)
🖥️ Clean GUI-based interface (no terminal needed)
🧠 How It Works

DeepSecure combines multiple detection techniques:

DCT Analysis → Detects high-frequency GAN artifacts
Texture Analysis → Identifies unnatural skin smoothing
Lighting Consistency → Detects sudden illumination changes
Face Stability → Tracks jitter/flickering across frames
Blink Detection (EAR) → Identifies unnatural eye behavior
Emotion Analysis (DeepFace) → Checks expression consistency

All signals are combined into a final Deepfake Risk Score (%).

🛠️ Tech Stack
Python
OpenCV
DeepFace (optional AI layer)
dlib (for facial landmarks)
Tkinter (GUI)
⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/RajatZode/DeepSecure-AI-for-Job-Interviews
cd deepsecure

2️⃣ Install required modules
pip install opencv-python numpy
pip install deepface
pip install dlib

⚠️ Important Setup (for full features)
📌 Facial Landmarks (Blink Detection)

Download:
👉 http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2

Extract the file
Place it in the project folder
▶️ Run the Application
python main.py

🧪 Usage
Option 1: Upload Video
Click UPLOAD VIDEO
Select interview recording
System analyzes frames and gives result
Option 2: Live Webcam
Click LIVE WEBCAM
Records ~15 seconds
Displays real-time detection
📊 Output
Deepfake Risk Score (%)
Verdict:
✅ Likely Genuine
⚠️ Suspicious
❌ No Valid Subject
Metrics:
Face presence
Blink rate
Frame risk
Emotion variation
🔊 Alerts
🔔 Genuine → Soft Ding
🚨 Suspicious → Alarm Sound
🔇 No alert if no face detected
🚧 Limitations
Not a fully trained deep learning deepfake model (prototype stage)
Accuracy depends on lighting and video quality
DeepFace & dlib are optional but improve detection
🔮 Future Improvements
Real-time interview integration (Zoom, Meet)
Advanced deepfake detection models (CNN / Transformer)
Cloud deployment (Vercel + API backend)
Recruiter dashboard & analytics
Multi-face detection & identity verification
💡 Innovation

Unlike general deepfake tools, DeepSecure is:

🎯 Interview-focused
⚡ Real-time ready
🔐 Security-layer oriented
📈 Lightweight & scalable
🤖 AI-upgradable architecture
👨‍💻 Author

Rajat Zode
B.Tech IT Student | Aspiring Security Engineer

⭐ If you like this project

