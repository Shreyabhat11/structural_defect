# 🏗️ Construction Defect Detection System (Prototype)

An AI-powered construction defect analysis system that uses Google Gemini Vision to detect and assess structural defects from uploaded site images.  
This prototype is intended to assist civil and structural engineers in preliminary defect identification, severity assessment, and remediation planning.

---

## 🚀 Features

- Image-based construction defect detection
- Identification of cracks, holes, bends, and structural damage
- Probability and severity assessment of defects
- Engineering insights on defect causes and propagation
- Live load capacity reduction estimation
- Recommendations for rectification and repair methods
- Rebar placement and concrete grade impact analysis
- Slab rejection criteria and code compliance indicators
- Suggestions for NDT and long-term monitoring

---

## 🧩 Tech Stack

- Frontend/UI: Streamlit
- AI Model: Google Gemini (Vision-enabled)
- Image Processing: Pillow (PIL)
- Environment Management: python-dotenv

---

## 📂 Project Structure

.
├── app.py
├── .env
├── requirements.txt
└── README.md

---

## 🔑 Environment Setup

### 1. Clone the Repository

git clone https://github.com/your-username/construction-defect-detection.git  
cd construction-defect-detection

---

### 2. Create and Activate Virtual Environment (Recommended)

python -m venv venv  

Linux / Mac:
source venv/bin/activate  

Windows:
venv\Scripts\activate

---

### 3. Install Dependencies

pip install -r requirements.txt

---

## 🔐 Configure Gemini API Key

Create a `.env` file in the root directory and add:

GOOGLE-GEMINI-API-KEY=your_api_key_here

Important: Do not commit the `.env` file to version control.

---

## ▶️ Run the Application

streamlit run app.py

The application will open automatically in your default browser.

---

## 🧪 How the Application Works

1. Upload a construction image using the sidebar
2. Click the "Analyze for Defects" button
3. The system sends the image and a structured engineering prompt to Gemini
4. The AI returns a concise, expert-style defect analysis
5. Results are displayed directly in the UI

---

## 📌 Prompt Design Overview

The AI model is instructed to:
- Act as a Structural and Civil Engineer
- Provide crisp bullet-point responses
- Limit answers to 1–2 lines per question
- Analyze 13 key engineering parameters including:
  - Defect probability and severity
  - Causes and propagation conditions
  - Load capacity reduction
  - Rectification methods
  - Code compliance and safety implications

---

## ⚠️ Disclaimer

This application is a prototype for educational and decision-support purposes only.  
It does not replace professional site inspections, structural testing, or certified engineering judgment.

---

## 🛣️ Future Enhancements

- Mobile application integration for on-site inspections
- Defect tracking and remediation database
- Automated PDF report generation
- Engineering analytics dashboard
- Fine-tuned AI models trained on domain-specific defect images

---

## 📄 Version

Prototype Version: 1.0
