# 🔐 Cyber Risk Assessment & Threat Intelligence Platform

## 📌 Introduction
This project is a Python-based platform that automates cyber risk assessment by combining network scanning and threat intelligence. It analyzes targets, calculates risk scores, and displays results using a dashboard.

---

## 🎯 Objective
- Perform network scanning using Nmap  
- Integrate threat intelligence using VirusTotal  
- Calculate risk scores based on scan results  
- Store and manage scan data  
- Visualize results using a dashboard  

---

## 🧱 Project Structure
```
Cyber-Risk-and-Threat-Intelligence-platform/
│
├── dashboard.py                  # Streamlit dashboard
├── database.py                   # Data storage handling
├── requirements.txt
├── sample_test_targets.txt       # Sample targets
│
├── scans/                        # Saved scan results (XML)
│   ├── scanme.nmap.org.xml
│   └── testasp.vulnweb.com.xml
│
├── scanners/
│   ├── risk_scoring.py           # Risk calculation logic
│
│   ├── nmap_scanner/
│   │   └── nmap_scanner.py       # Nmap scanning module
│
│   └── vt_scanner/
│       └── vt_scanner.py         # VirusTotal scanning module
```

---

## ⚙️ Technologies Used
- Python  
- Nmap (Network scanning)  
- VirusTotal API (Threat intelligence)  
- Streamlit (Dashboard)  
- Pandas (Data processing)  
- Requests (API handling)  

---

## 🔍 Module Description
- **nmap_scanner.py** → Performs network scanning using Nmap  
- **vt_scanner.py** → Fetches threat intelligence from VirusTotal  
- **risk_scoring.py** → Calculates risk score based on scan results  
- **dashboard.py** → Displays scan results and risk analysis  
- **database.py** → Stores and manages scan data  

---

## 📊 Risk Scoring
The system calculates risk based on:
- Open ports and services  
- Known vulnerabilities  
- Threat intelligence results  

Final score represents the overall security risk of the target system.

---

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run Dashboard
```bash
streamlit run dashboard.py
```

---

## 🌐 Tools Used
- Nmap → https://nmap.org  
- VirusTotal → https://www.virustotal.com  
- Streamlit → https://streamlit.io  

---

## 📸 Screenshots
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/7e40ed15-f3c1-44d8-a47d-fe2acf22ec80" />


---

## 👤 Author
Akshay Bakale  

---

## 📌 Conclusion
This platform provides an automated approach to cyber risk assessment by integrating network scanning and threat intelligence. It helps identify vulnerabilities and supports better security decision-making.
