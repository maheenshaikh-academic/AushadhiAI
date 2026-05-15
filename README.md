# Aushadhi AI

> Scan. Verify. Heal.

AushadhiAI is an AI-powered healthcare web application that helps users identify medicines, detect fake medicines, check drug interactions, compare prices, and understand medicine usage in a simple and interactive way.

The platform is designed especially for non-technical users, elderly users, and multilingual users by providing voice support, image-based recognition, and a guided user experience.

---
# Project Demo Video
https://drive.google.com/file/d/1j58abAKhVcvIbHX5mGWXh_KJiqbnlKaJ/view?usp=drivesdk
# Features

## Medicine Image Recognition

* Upload or capture a medicine image
* Detect tablets, strips, bottles, and packaging
* Recognize medicine name and category using AI models

## Fake Medicine Detection

* Analyze packaging and printed details
* Compare with original medicine database
* Show authenticity status:

  * Real
  * Suspicious
  * Fake

## OCR Text Extraction

* Extract medicine details from image
* Detect:

  * Medicine Name
  * Batch Number
  * Expiry Date
  * Manufacturer

## Drug Interaction Checker

* Add multiple medicines
* Detect harmful interactions
* Display warnings and safer alternatives

## Health Category Detection

* Identify category such as:

  * Antibiotic
  * Painkiller
  * Vitamin
  * Antacid
  * Syrup

## QR / Barcode Scanner

* Scan QR codes and medicine barcodes
* Fetch medicine details automatically

## Price Comparison

* Compare prices from multiple sources
* Suggest lower-cost generic alternatives

## AI Chat Assistant

* Ask medicine-related questions
* Example:

  * “What are the side effects of this medicine?”
  * “Is this medicine safe during fever?”

## Voice + Multi-Language Support

* Supports:

  * English
  * Hindi
  * Tamil
  * Telugu
  * Bengali
  * More regional languages
* Input methods:

  * Voice
  * Text
  * Image
* Output methods:

  * Text
  * Voice

## Interactive Mode

Interactive Mode is designed for users with little or no technical knowledge.

Features include:

* Large buttons
* Step-by-step guidance
* Voice-first navigation
* Read-aloud results
* Easy medicine scanning
* One-tap suggestions

---

# Screens

1. Landing Page
2. Login / Register Page
3. Interactive Home Screen
4. Scan Result Page
5. Drug Interaction Checker
6. AI Chat Assistant
7. User Dashboard

---

# Technology Stack

## Frontend

* HTML
* CSS
* JavaScript
* React.js
* Bootstrap / Tailwind CSS

## Backend

* Python
* Flask or Django

## AI / Machine Learning

* TensorFlow
* PyTorch
* OpenCV
* Scikit-learn
* Hugging Face Transformers

## OCR & Voice

* pytesseract
* Whisper
* SpeechRecognition
* gTTS
* pyttsx3

## Database

* SQLite
* PostgreSQL

---
# Installation

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/AushadhiAI.git
cd AushadhiAI
```

## 2. Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Required Python Libraries

```bash
pip install flask tensorflow torch torchvision opencv-python numpy pandas scikit-learn pytesseract pillow speechrecognition pyttsx3 gtts transformers deep-translator pyzbar
```

---

# Running the Project

## Backend

```bash
cd backend
python app.py
```

## Frontend

```bash
cd frontend
npm install
npm start
```

---

# Example User Flow

1. User opens Aushadhi AI
2. User logs in or continues as guest
3. User uploads or scans medicine
4. AI detects medicine name
5. System checks if medicine is real or fake
6. OCR extracts details
7. Results are shown in selected language
8. User can listen to the result using voice output
9. User can ask more questions using AI assistant

---

# Future Improvements

* Mobile App Version
* Offline Scanning
* Doctor Consultation Feature
* Nearby Pharmacy Locator
* Emergency Medicine Alert
* Health Report Export
* Cloud-Based Medicine Database

---

# Contributors

* Project Name: AushadhiAI
* Developed for smart medicine recognition and healthcare assistance

---

# License

This project is licensed under the MIT License.

---

# Tagline

**Aushadhi AI – Scan. Verify. Heal.** 🌿🤖
