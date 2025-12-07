# Email Header Forensic Analysis — Manual & Tool-Based Investigation

This repository contains two simulated forensic analysis reports focused on identifying phishing, spoofing, and email authentication failures through **manual header inspection** and **tool-based analysis** using MXToolbox.

Both reports were created as part of cybersecurity, fraud detection, and digital forensics skill-building.

---

## 🎯 Objectives of This Project

- Understand how email headers reveal sender identity and routing  
- Detect signs of phishing, spoofing, and domain impersonation  
- Interpret authentication mechanisms:
  - SPF  
  - DKIM  
  - DMARC  
- Compare manual inspection results with automated tool output  
- Build practical forensic reporting skills  

---

## 🛠 Methods Used

### **1. Manual Header Inspection**
- Extraction of header using *Show Original*  
- Analysis of:
  - Return-Path  
  - Received hops  
  - Message-ID  
  - Sending IP & geolocation  
  - SPF / DKIM / DMARC results  
  - Domain reputation indicators  

### **2. Tool-Based Analysis (MXToolbox)**
- Verification of SPF, DKIM, and DMARC alignment  
- Spam score indicators  
- Routing path interpretation  
- Comparison with legitimate email header  

---

## 🔍 Key Findings

### **Simulated Phishing Email**
- SPF: ❌ Failed  
- DKIM: ❌ Failed  
- DMARC: ❌ No policy found  
- IP reputation: Suspicious origin  
- Domain: Look-alike fraudulent domain  
- Conclusion: **Likely spoofed email**

### **Legitimate Email**
- SPF: ✔ Passed  
- DKIM: ✔ Passed  
- DMARC: ✔ Passed  
- Routing: Valid and consistent  
- Conclusion: **Authentic communication**

--- 

## 📂 Project Files

To view or download, click:

- [Manual Email Header Analysis](./Email_Header_Analysis.pdf)  
- [Tool-Based Email Header Analysis](./Email_Header_Tool_Analysis.pdf)

--- 

## 📖 Transparency

This is a simulated educational project created by **Adheena M** to develop skills in digital forensics, fraud analysis, and cybersecurity.

ChatGPT was used only for conceptual guidance.  
All report writing, interpretation, analysis, and formatting were completed manually.
