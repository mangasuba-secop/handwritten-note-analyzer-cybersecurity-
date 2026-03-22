# handwritten-note-analyzer-cybersecurity-
# 🛡️ Handwritten Note Analyzer (Cybersecurity Project)

## 📌 Overview
This project is a Python-based handwriting analysis tool designed for cybersecurity investigations. It processes images of handwritten notes, extracts text using OCR, and flags potentially sensitive or suspicious keywords.

This tool simulates how analysts might triage handwritten evidence in fraud cases, insider threats, or incident response scenarios.

---

## 🎯 Objectives
- Extract text from handwritten notes
- Identify suspicious keywords related to security risks
- Generate structured outputs for investigation use
- Demonstrate practical OCR + cybersecurity integration

---

## ⚙️ Technologies Used
- Python
- OpenCV (image preprocessing)
- pytesseract (OCR engine wrapper)
- Tesseract OCR

---

## 🧠 How It Works
1. Loads a handwritten image
2. Converts it to grayscale and applies noise reduction
3. Uses thresholding to improve OCR accuracy
4. Extracts text and positional data using Tesseract
5. Flags suspicious keywords such as:
   - password
   - admin
   - login
   - bitcoin
   - confidential
6. Outputs:
   - Extracted text file
   - JSON investigation report
   - Annotated image with bounding boxes

