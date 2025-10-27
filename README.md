# 📧 AI-Powered Email Spam Checker Pro

**AI-Powered Email Spam Checker Pro** is a smart Python-based GUI application that detects **spam and phishing emails** using:
- AI-assisted keyword matching (multi-language)
- Heuristic URL scanning
- Real-time VirusTotal API integration
- Tkinter-based live email analysis GUI

This tool is designed for cybersecurity enthusiasts and analysts to **detect and analyze suspicious email messages** safely and locally.

---

## 🚀 Features

✅ **Multi-language support** — Detects spam in English, Hindi, Arabic, and Spanish  
✅ **VirusTotal integration** — Checks each URL for malicious behavior via API  
✅ **Heuristic URL scanning** — Detects obfuscated or malicious-looking links  
✅ **Keyword-based scoring system** — Flags common spam patterns intelligently  
✅ **Batch mode & Live mode** — Paste multiple emails or check in real-time  
✅ **Simple GUI** — Built with Tkinter for ease of use  

---

## How It Works

1. Paste your email content in the input box.  
2. (Optional) Separate multiple emails with a line containing only:

3. Click **“Check Emails”** to analyze.  
4. The tool will:
- Detect language  
- Analyze spam keywords  
- Extract URLs and evaluate them  
- Use **VirusTotal API** to verify suspicious links  
- Display clear results below  



## ⚙️ Installation

### 1️⃣ Clone the repository

git clone https://github.com/ghostempireis/AI-Powered-Email_Spam-checker_Pro.git
cd AI-Powered-Email_Spam-checker_Pro

2️⃣ Install dependencies

pip install langdetect requests


Add your VirusTotal API Key

Open the Python file and replace:
VT_API_KEY = "your_api_key_here"



🧩 Usage

python3 main.py


🖥️ GUI Preview

📧 Email Spam Checker - Pro
-------------------------------------------
Paste one or more emails below.
Use a line with --- to separate emails.
[ Check Emails ] [ Clear ] [ Live Mode ]
-------------------------------------------
Results:
✅ Not Spam / 🚫 Spam or Phishing Suspected


🧠 Tech Stack

Python 3.x
Tkinter (GUI)
langdetect (language detection)
requests (VirusTotal API)
Regex + Heuristic Analysis

⚠️ Disclaimer

This tool is for educational and research purposes only.
Always verify analysis results before taking any action.
API usage may be subject to VirusTotal’s rate limits.

👨‍💻 Author

👾 Ghost Empire (Ranjan Kumar)
🧑‍💻 Ethical Hacker & Cybersecurity Researcher
🔗 GitHub : https://github.com/ghostempireis
