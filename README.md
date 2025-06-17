🚗 AI-Powered License Plate Recognition System

This project is an AI-based license plate recognition system built using OpenCV and Tesseract OCR. It achieves over 90% accuracy in detecting and reading vehicle license plates, with support for real-time processing and speech-to-text input handling.
🔍 Features

    ✅ License Plate Detection using OpenCV image preprocessing

    ✅ Text Extraction with Tesseract OCR (over 90% accuracy)

    ✅ Real-Time Performance optimized with streamlined pipeline

    ✅ Speech-to-Text Input Support for voice-based queries

    ✅ Regex-Based Validation to ensure extracted plate format accuracy

🧠 Tech Stack

    Python

    OpenCV

    Tesseract OCR

    SpeechRecognition / PyAudio

    Regex

    Flask (optional for integration into web app)

📂 Project Structure

├── images/                # Sample input images
├── processed/             # Output images with detected plates
├── src/
│   ├── plate_detector.py  # OpenCV detection logic
│   ├── ocr_reader.py      # Tesseract OCR logic
│   ├── speech_input.py    # Voice command handler
│   └── main.py            # Main pipeline
├── requirements.txt
└── README.md

🚀 How to Run

    Clone the repository:

git clone https://github.com/your-username/license-plate-recognition.git
cd license-plate-recognition

    Install dependencies:

pip install -r requirements.txt

    Run the main script:

python src/main.py

📊 Results

    Average detection accuracy: ~90%

    Real-time processing latency: < 1 second

    Tested on 150+ real-world Indian vehicle images and videos

📢 Demo

    Coming soon — hosted version or demo video link (optional)

🤝 Contributions

Feel free to fork, raise issues, or open PRs to improve accuracy or add new features (e.g., regional number plate formats, mobile deployment, etc.)
📬 Contact

Madhuri Gade
📧 madhurigade000@gmail.com
🔗 LinkedIn
🔗 GitHub
